# Dog breed classifier
This is a project completed as part of the Udacity Data Science Nanodegree. The corresponding blog post can be found [here.](https://medium.com/@michaelnasra/how-i-trained-a-machine-learning-model-to-identify-dog-breeds-7f3e8d406d35)
##### Software used
- Python 3.8.1
##### Libraries used
- sklearn
- keras
- numpy
- glob
- pandas
- matplotlib
- random
- cv2
- keras
- tqdm
- PIL

##### Motivation
In this project we look to create a deep learning model that can receive a picture of a dog and identify what breed of dog it is. This is an interesting problem because if successful it could be useful in reducing the amount of manual effort required to categorise large volumes of unlabelled image data.

##### Files included in the repository
- dog_app.ipynb - Notebook containing the code used to generate the model and outputs.
- extract_bottleneck_features.py - Python file provided in skeleton code that extracts bottleneck features from pretrained models.
- LICENCSE.txt - Udacity licencse file
- bottleneck_features - Folder where you should store the bottleneck features file (link to download is in the dog_app notebook)
- haarcascades/haarcascade_frontalface_alt.xml - Pretrained model that can identify whether human faces are present in a photo.
- images - Folder that contains a variety of testing images and images used for descriptive purposes in the notebook.
- requirements - Folder that contains requirements files for a variety of operating systems
- saved_models - Folder that stores saved models after they have been created by the dog_app notebook.

##### Results
The included notebook is able to create a transfer learning model that achieves a 79% accuracy identifying dog breeds correctly on the testing data.

##### Acknowledgements
Thanks to Udacity for providing the skeleton code that was used to complete this project.