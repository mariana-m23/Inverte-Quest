# Inverte-Quest
NSF Project that will allow users to submit images of any invertebrate. Where the user will then receive a classification of the organism with a short biography, to give an insight into the organisms behavior.
Inverte-Quest is a new app that permits users to learn about invertebrates, know about their habitat, their different lifestyle and how they live their life. This app was created to help classify organisms as often many invertebrates are confused for one another.
Inverte-Quest wsas created using Segment Anything A.I. to mask and outline the organism in the photo that is submitted to the app. After it is masked the image then goes into ResNet to be classified after 

# Instructions for how to develop, use, and test the code.
follow the SAM AI instructions : https://github.com/mariana-m23/segment-anything-research

## Install Segment Anything:

  - pip install git+https://github.com/facebookresearch/segment-anything.git
- or clone the repository locally and install with:
    -  git clone git@github.com:facebookresearch/segment-anything.git
  -  cd segment-anything; pip install -e 

## Model Checkpoint:

## Adding Pinata 
Stores and retrieves content with security. Utilize the API Key that is with the Public IPFS
  
