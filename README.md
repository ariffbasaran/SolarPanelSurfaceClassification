# Solar Panel Surface Classifier

## Overview
This project aims to classify various surface conditions of solar panels using deep learning models. The models are trained to identify and classify different states such as clean, dusty, bird-dropped, electrical damage, physical damage, and snow-covered surfaces on solar panels.
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/f66cc334-9380-437a-a0b3-5563e9fadbf2)


## Models and Results
The project experimented with three different deep learning architectures:
- DenseNet121
- EfficientNetB0
- VGG

Each model was trained and evaluated on the dataset, achieving the following results:
## -  DenseNet121:
  ![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/53e2182b-a012-4bad-b551-5ce37f462915)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/5a9b9ced-e118-4d44-83d1-3d19e16e7b57)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/61ed1e9d-2348-43fe-8f08-7a765a9ddcfb)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/b902e6f3-969a-4fa3-86f9-e3a5df4da459)

## - EfficientNetB0:
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/ad35a036-9b01-4b2c-8a1c-60277ebe50c1)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/3758e03a-bf07-4d54-9989-ab9e85c48d6b)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/dad43897-36d2-44dc-85c7-f4f8104b033e)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/8ecbdc89-0ed6-4b16-ad14-e95fc5b72e5b)

## - VGG:
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/4b685ddb-c9d8-458d-b022-7c33610d44c2)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/a98984c1-b792-4e82-82e4-5818b48cb086)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/86d0263c-b421-4810-9132-3af3af3c3a7a)
![image](https://github.com/ariffbasaran/SolarPanelSurfaceClassification/assets/109107707/bb55be96-d64c-4bbe-a16a-888e5c318875)


The comparison indicates that DenseNet121 performed slightly better than the other models in accurately classifying various surface conditions.

## Dataset and Classes
The dataset used in this project consists of images scraped from the internet. It includes six different classes:
1. Clean
2. Dusty
3. Bird-drop
4. Electrical Damage
5. Physical Damage
6. Snow-covered

## Usage and Installation
To use this project, follow these steps:
1. Clone the repository.
2. Install the necessary dependencies.
3. Run the model training script.

## Conclusion and Recommendations
The developed model showcases promising accuracy in classifying surface conditions of solar panels. Further improvements could involve data augmentation techniques and fine-tuning hyperparameters to enhance the model's robustness and generalization.


