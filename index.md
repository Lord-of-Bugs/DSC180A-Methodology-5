# DSC180A Methodology Assignment 5

## Personal Information

- Name: Muchan Li
- Email: mul005@ucsd.edu
- Section: A01
- Mentor: Professor Albert Hsiao

## Proposal Brainstorm

1. The most important topic we learned was to cleverly turn classification tasks into regression tasks, thereby saving manual labor on labeling data points/objects. In the process, we also learned about some of the crucial differences between regular images and X-ray images, where we particularly emphasized the more expanded dynamic range of radiographs and the challenge it would pose to deep neural network training if not properly normalized.
2. Since both the reference paper and our group have seemed to reach a bottleneck in making more accurate prediction, I would want to investigate the possible improve to model performace by scaling the same image with different 3 dynamic ranges and wrap that together as my RGB image to input to the neural network. On top of it, I would also like to investigate the possible implementation of an auto-encoder on the radiographs, and combine the encoder features with some text embeddings to jointly establish a multi-modal LLM that assists in providing diagnostic suggestions and is able to improve its suggestions based on feedbacks.
3. As mentioned, I would like to encode the RGB layers of the input radiographs differently by scaling the image to different dynamic ranges across each. This approach aims to mimic the functionality of dynamically adjusting radiograph resolution and intensity as described by Professor Hsiao.
4. As mentioned in #2, I would first like to put together the LLM-based diagnostic "assistant" that can help outline symptoms for diagnosis and generate reports. Additionally, if possible, I would like to incorporate user feedback into re-training the model to iterate on its previous, unsatisfactory predictions.
