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
Our final code submission is the main branch of the "DeepLearningProject_Group2.ipynb" file. It includes model exploration, model development, training, and demonstrates functionality of our final trained model. Our trained model is store on Kaggle at the link below.

Final Model Link: https://www.kaggle.com/simran11011/vgg-model?select=group2_vgg_segmentation.h5


### Demonstration of Project Requirements

The final cell of our code submission, titled "Running Final Model," demonstrates fulfilment of the 3 project requirements. The final cell loads our trained model, outputs performance metrics using provided masks, displays segmentation masks, and shows examples of our collision detection algorithm. Only code essential to demonstrating the 3 project requirements is included in the final cell.


### Datasets for models:
Full Dataset (Provided in project outline): https://www.kaggle.com/bulentsiyah/semantic-drone-dataset

Google Maps Images: https://www.kaggle.com/simran11011/sep769-group-2-dataset


## Requirements for Running Code Submission:
* Download the Full Dataset and extract into a selected folder
* Download model and code submission into the selected folder
* Download the Google Maps Images and extract into the selected folder
* The selected folder should now have the following contents and the final submission is ready to run
  * RGB_color_image_masks
  * dataset
  * gmaps_images
  * DeepLearningProject_Group2.ipynb
  * group2_vgg_segmentation.h5
  * class_dict_seg.csv
