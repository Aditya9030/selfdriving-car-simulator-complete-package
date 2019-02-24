# selfdriving-car-simulator-complete-package
This repository is a ready to use package for running the udacity self driving simulator with zero knowledge on python or deep learning.....NOTE:there is no need to download any other repository from github.
this repository consists both the simulator(which is completely built up on unity) and the code required to train and run the simulator.

Step by step procedure is as follows:

1)navigate into the downloaded repository and open cmd in that folder.
2)run this command 

"pip install -r requirements.txt".

3)download and install the unity download assistant.(this might take a while).

4)download and install the git lfs software.

5)now open the "executable simulator" folder from the downloaded repository and open "exec" unity file,set the resolution,press play.

6)now open "how_to_simulate_a_self_driving_car" folder and open cmd in that file.

7)now run this command in the command prompt 
  
  "python drive.py model-mix.h5" 
  
  to run the car with pretrained values of weights of the convolutional neural network.
8)now run the simulator in the autonomous mode and the car will drive itself

9)to train the model with your own data collect the data from the simulator in the training mode by recording the driving pattern.

10) then run the command "python model.py" in command prompt in the folder "how_to_simulate_a_self_driving_car"

a hearty thanks to siraj raval for helping me do this project....i just made it easy to use for beginners by adding a built simulator in unity
