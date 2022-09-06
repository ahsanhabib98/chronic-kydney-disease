# Geo-hex object tracking
## Run the following commands to get started:
You have to download and set up anaconda to follow this command.
Please download the [Anaconda](https://www.anaconda.com/products/individual#Downloads) and set up.
### For rcnn
````
cd geohex_bubble_tracking/rcnn
conda create -n env_name python=3.7.10
conda activate env_name
conda install -c conda-forge notebook imgaug=0.4.0 imutils=0.5.4 tqdm=4.62.3 pydicom=2.2.1
conda install -c conda-forge numpy=1.20.3 pandas=1.3.0 matplotlib=3.4.2 scikit-image=0.17.2
conda install -c conda-forge keras=2.2.4 opencv=4.1.0 tensorflow=1.14.0
Jupyter notebook
````
### For opencv
````
cd geohex_bubble_tracking/opencv
conda create -n env_opencv python=3.7.10
conda activate env_opencv
conda install -c conda-forge notebook imgau=0.4.0 imutils=0.5.4 tqdm=4.62.3 pydicom=2.2.1
conda install -c conda-forge numpy=1.21.1 pandas=1.3.1 matplotlib=3.4.2 scikit-image=0.18.1
conda install -c conda-forge opencv=4.0.1
````
#### For bubble
````
cd geohex_bubble_tracking/opencv/Bubble\ tracking
python3 bubble_tracking.py
````
#### For droplet
````
cd geohex_bubble_tracking/opencv/Droplet\ tracking
python3 droplet_tracking.py
````
