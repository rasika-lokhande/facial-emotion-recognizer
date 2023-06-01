# Real time facial emotion detector from a live video stream

In this project, I have developed a webapp, which can be deployed on your local server, which classifies facial expressions into seven categories of emotions - angry, disgusted, fearful, happy, neutral, sad and surprised. 

The CNN model is trained on the **FER-2013 dataset**, which consists of 35887 grayscale images, each with resolution of 48 x 48 pixels. 



## Table of Contents

1. [Installation] (## Installation)

 
## Installation

To install the app on your local server,

1. Ensure that the dependencies are installed on your system
    a) python
    b) opencv
    c) tensorflow

2. Download the following files
    a) index.py
    b) templates folder
    c) camera.py
    d) model.py
    e) model_structure.json
    f) model_weights.h5

3. Go the the Command Prompt, and go to the directory where the above files are located, and run the following command.

```bash
python index.py
```

