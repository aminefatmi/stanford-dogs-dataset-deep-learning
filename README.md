# stanford-dogs-dataset-deep-learning

The aim of this project is to build a CNN model for dog breeds classification.  

## Stanford dogs dataset:  
http://vision.stanford.edu/aditya86/ImageNetDogs/  

## Notebooks:  
 - PStanford_01_CNN_from_scratch_10_breeds.ipynb   --> EDA + CNN from scratch using 10 breeds only  
 - PStanford_02_transfer_learning_10_breeds.ipynb  --> Transfer Learning models using 10 breeds  
 - PStanford_03_transfer_learning_120_breeds.ipynb --> Using best model from previous notebook + Fine-tuning on the entire dataset (120 breeds)  

## Powerpoint:  
 - PStanford_04_slides.ppt --> support for presentation  

## App folder:  
 - inceptionV3_120_breeds_best.json  --> inception fine-tuned model (120 breeds)  
 - inceptionV3_120_breeds_best.h5    --> corresponding model weights  
 - class.pkl                         --> dictionary with class_names as keys and class_indices as values  
 - app.py                            --> python script for dog breeds prediction. It takes an URL image as input and return the breed with highest probability  



