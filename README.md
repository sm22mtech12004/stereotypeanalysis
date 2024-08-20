# stereotypeanalysis
The primary goal of this project is to analyze and quantify gender-based stereotypes by studying the roles assigned to male and female characters. The project aims to develop a machine learning solution
Dataset
The dataset used for this project includes:

Movie Scripts: Textual data representing the narrative and dialogues of the movies.
Movie Trailers: Visual and audio data used for promoting the movies.
Wikipedia Data: Structured and unstructured data from Wikipedia pages about the movies.
Movie Posters: Visual data in the form of images, used for marketing the movies.
Methodology
1. Face Detection and Gender Detection
To analyze the gender distribution and representation in movie posters:

Face Detection: Used the MTCNN (Multi-task Cascaded Convolutional Networks) algorithm to detect faces in movie posters.
Gender Detection: Applied the VGG16 model, pre-trained on the ImageNet dataset, for gender classification of detected faces.
The code for this part of the analysis is available in the repository.
