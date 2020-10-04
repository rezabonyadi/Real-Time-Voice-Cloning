# Real-Time Voice Cloning
See the parent repo here: https://github.com/CorentinJ/Real-Time-Voice-Cloning

The parent is compatible with orginal Python disctribution and gives errors when it is installed under Annaconda distribution. 

Many windows users also have difficulties installing and using this repo. 

This clone has an environment.yml, which can be used directly in annaconda distribution. It is also compatible with Windows 10, tested.

Step by step: 
- Clone the repo
- open a terminal and navigate to the directory where this repo was cloned
- type in "conda env update environment.yml", which would install a new environment for you with all required libraries to run the program
- type in "conda activate voice_clone", which activates the "voice_clone" environment
- type in "python demo_toolbox.py"

You need to ensure that you have necessary CUDA-related libraries installed already, if using GPU of course.



