# SelfDriveDIP
### NOTE: This project is a work in progress.

## Objective: To simulate a self Driving car using Udacity's open source emulator.

### How do self Driving cars generally work?

**Think about an analogy where we humans are driving. We continuously take inputs from our surroundings and simultaneously process it in order to make decisions on which way to turn the steering wheel.
This can be translated into a machine problem called SLAM or Simultaneous Localization and Mapping.**

Traditionally, self driving car has been about Reinforcement Learning algorithms to continuously correct its driving capabilities but that's not enough. Roads are complex! There are weather conditions that requires you to change the way you accelerate, different kind of road signs and situations that we probably could never predict.
You also need to predict the actions of others along with your own actions so that you don't come across speeding cars and dead babies or Pokemons.

This project is an implementation of the paper published by NVidia.

### Dependencies Used:
    - python==3.5.2
    - numpy
    - matplotlib
    - jupyter
    - opencv3
    - pillow
    - scikit-learn
    - scikit-image
    - scipy
    - h5py
    - eventlet
    - flask-socketio
    - seaborn
    - pandas
    - imageio
    - pip:
        - moviepy
        - tensorflow==1.1
        - keras==1.2
