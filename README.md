# Facial Alignment Exercise

Play around with facial alignment techniques.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

This project uses Python >= 3.7. See requirements.txt for a list of dependencies.

### Installation

A step by step series of examples that tell you how to get a development env running.

The use of virtualenv is encouraged. See this [gist](https://gist.github.com/hsuanhauliu/1b1fed24baa1cbb6d2d191e8ea85b8ec) on how to install and activate virtualenv.

1. Clone the repository and download dependencies.

```
git clone https://github.com/hsuanhauliu/facial-alignment-exercise.git
cd facial-alignment-exercise
pip install -r requirements.txt
```

If you have trouble downloading dlib, please follow this [tutorial](https://www.pyimagesearch.com/2017/03/27/how-to-install-dlib/) to troubleshoot.

2. Download [Openface](https://github.com/cmusatyalab/openface).

```
git clone https://github.com/cmusatyalab/openface.git
cd openface
pip install -r requirements.txt
sudo python setup.py install
```

3. Download the pre-trained model [here](dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place it in the root directory.

4. Add your virtual environment to the kernel.

```
ipython kernel install --user --name=venv
```

Reference: https://medium.com/@eleroy/jupyter-notebook-in-a-virtual-environment-virtualenv-8f3c3448247


### Usage

Follow the commands below to run the program.

```
jupyter notebook facial-alignment.ipynb
```

## References

- [Python Computer Vision OpenCV - Find Face Landmarks using DLIB](https://www.youtube.com/watch?v=ujYc-3na6XU)
