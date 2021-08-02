## SEP 769 (Cyber Physical Systems) Deep Learning Project, Project 3 - Aerial Perspective Object Detection (Group 2)

### Project Description
Drone and aerial picture-taking quality has improved drastically in the past decade. Drone stabilization allows pictures taken from an aerial view to be crystal clear without shaking or blurriness. This has many practical and exciting applications for photography, cinematography, and also image recognition! Drone images can be used to quickly identify people and seek out specific objects in a large area. Think of how this could be used for spotting survivor rescues in disaster-struck areas.

The Semantic Drone Dataset focuses on semantic understanding of urban scenes for increasing the safety of autonomous drone flight and landing procedures. The imagery depicts more than 20 houses from nadir (bird's eye) view acquired at an altitude of 5 to 30 meters above the ground. A high-resolution camera was used to obtain images at a size of 6000x4000px (24Mpx).

The dataset consists of 400 images that have been annotated according to twenty standard classes such as trees, persons, cars, and pavement.

Project Outcomes:

* Identify everyday objects such as cars and roads in bird's eye view images
* Use a trained model to identify objects over a large, continuous, mapped area (i.e., your local neighborhood from google maps)
* Use the positioning of cars and people determined to flag areas where pedestrians may be at most risk of an accident

## Code Submission
Our final code submission is the main branch of the "DeepLearningProject_Group2.ipynb" file. It includes model exploration, model development, training, and demonstrates functionality of our final trained model. 

### Code Run Setup

In order to run the notebook through Google Colab, data inflow is setup through a connection to a shared Google Drive folder. Those who have access (received via email) can mount the drive when running the code in order to pull in all the necessary image data. The notebook can be opened in Colab through GitHub if the same email is used for the GitHub account as is the one given access to the shared folder. Once the notebook is open in Google Colab with the account corresponding to the email given shared access, the notebook can be run in its entirety.
