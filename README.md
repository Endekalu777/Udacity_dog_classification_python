# Image Classification Dog Breed
This project was created by Udacity for AI Programming with Python Nanodegree program.

# How to Start
Create a local virtual env with virtualenv venv
Activate the local virtual env source venv/bin/activate. If you need to deactivate just command deactivate
Install dependencies pip install -r requirements.txt
Move to application folder folder cd intropyproject-classify-pet-images
Run the application with only one CNN architecture model python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
Run the application for folder pet_images with all 3 CNN architecture model and print results sh run_models_batch.sh
Run the application for folder uploaded_images with all 3 CNN architecture model and print results sh run_models_batch_uploaded.sh


# Intro to Python Project - Classifying Pet Images: Determine which CNN architecture model works best at classifying images of dogs and their breeds.
Each directory has a requirements.txt describing the minimal dependencies required to run the notebooks in that directory.

pip
To install these dependencies with pip, you can issue pip3 install -r requirements.txt.
