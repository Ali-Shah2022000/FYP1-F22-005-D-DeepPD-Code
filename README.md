# FYP1-F22-005-D-DeepPD-Code

# Summary
It is a development-based project in which we aim to develop a software that will aid in constructing 
Realistic Images from free hand sketches. The aim of this project is to aid in criminal forensics. Usually after a crime scene where there is no trace or evidence of culprit usually with the help of an eye witness an expert sketch artist is called to sketch the face of culprit but still the generated sketch may have some imperfections in it. So to automate this tedious work we have come up with deep portrait drawing. A novel approach to generate realistic human faces from mere free hand sketches even people with little drawing knowledge can generate a face and moreover to generalize the image editing facility too is provided in the application.

# Architecture overview
Free-hand sketches or roughly drawn sketches do not provide much information about the person being drawn. A naive person could draw sketches that may be incomplete or do not appear to be appealing in the eye of the viewer. So, we came up with a deep learning model that would take input sketches from the user that would be converted into realistic looking face images which would depict his sketch drawing.
This Model is based on 3 different modules which includes Component Embedding Module, Feature Mapping Module and Image Synthesis Module. A cross platform application would provide a canvas for the user to draw their sketches and the system will:

->Generate realistic image from sketch

->Give interface to edit the features of generated image

->Enable user to download the resultant image

->Extract data from CelebAMask-HQ for customized dataset preparation and collecting free-hand sketches for test data for our model

->Edge extraction of the input images and performing part level segmentation

->Developing a component embedding module for input freehand sketches and refining the sketches 

->Developing Feature mapping module 

->Designing an Image Generation Module/image synthesis module so that freehand sketches are converted to images 

->Providing a cross-platform application for the end user.
