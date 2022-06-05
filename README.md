# Terrain-Detection-IMU
Classifying terrain type based on time-series data gathered by inertial measurement unit (IMU) in lower-limb robotic prosthetic.


The aim of the project is to develop a terrain identification system based on inertial measurement units IMU streams collected from the lower limb. With such information, the control of a robotized prosthetic leg can be adapted to changes in its surrounding.
The solution I came up with was to train a convolutional neural network to classify which terrain an unknown stream of data can represent. This allows for adjusting the prosthetic leg to the type of terrain (for example, grass or concrete).


The requirements for the Jupyter Notebook:

python==3.8
numpy==1.19.5
pandas==1.0.5
seaborn==0.10.1
tensorflow=1.x

The Grid Search over learning rates can take a substantial amount of time to run. The data files need to be located in the same folder as the notebook. The notebook can be run from top to bottom.
