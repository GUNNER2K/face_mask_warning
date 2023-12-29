# face_mask_warning" 

This Repo aims to contain a project that was created during the covid times. It wasnt pushed into this repo until now. The main aim of this porject is to first identify if a person is wearing a mask or not. If a person is found not wearing the mask , then the person is recognized and a warning message is sent to that person's whatsapp. The following procedures were implemented in order to achieve this . 

The mask on the face was recognized by a simple CNN built from scratch using Tensorflow 2.x .
The face of the person was recognized by RCNN which was implemented using transfer learning.
The person's data , including his/her name and phone number was stored in a simple MySQL database, hence once the face was identified, the name and phone number of that person was retrieved from the database and a message was sent.
Main Libraries used were OpenCV , tensorflow and keras which were all implemented using python 3.10.0.
The message was sent through whatsapp using a the pywhatkit library in python.

In order to run it first install the requirements by running the following command in the terminal : pip install -r requirements.txt .
Then add your photo in train folder and your phone number in keys.py. 
then run app.py . It should redirect you to a local server. 
