# **<div align="center"> <ins> User Manual</ins> </div>**

## Follow the given procedure to Setup and installation of required libraries
 **STEP 1:** Create an environment using the below commands
> * **Setup the pip package manager**
```
pip install -U pip
```
> * **Install the virtualenv package**\
The virtualenv package is required to create virtual environments. You can install it with pip:
```
pip install virtualenv
```
> * **Create the virtual environment**\
To create a virtual environment, you must specify a path. For example to create one in the local directory called ‘mypython’, type the following:
```
virtualenv mypython
```
> * **Activate the virtual environment**\
You can activate the python environment by running the following command:
```
source mypython/bin/activate
```

**STEP 2:** Install Python (We've used Python3.7) using the command
```
sudo apt install python3.7
```

**STEP 3:** Install Jupyter Nodebook using the command
```
pip install notebook
```

**STEP 4:** Install The following required libraries
> * **Install OpenCV using the command**
```
pip install opencv-python
```
> * **Install Numpy using the command**
```
pip install numpy
```
> * **Install Pandas using the command**
```
pip install pandas
```
> * **Install Dlib using the command**
```
pip install dlib
```
> * **Install Matplotlib using the command**
```
pip install matplotlib
```
> * **Install Scipy using the command**
```
pip install scipy
```

**STEP 4:** After above installations
> * ***Option 1:*** Either clone the repository using the below command, and move to directory **".../Smart_Monitoring_System/Code"** and open **'classroom monitor.ipynb'** in Jupyter Notebook. And pass the directory of **'shape_predictor_68_face_landmarks.dat'** file, where it is required in the code.     
```
https://github.com/dheeraj-2000/Smart_Monitoring_System.git
```

> * ***Option 2:*** Or, After Unzipping this folder, move to **".../Smart_Monitoring_System/Code"** and open **'classroom monitor.ipynb'** in Jupyter Notebook. And pass the directory of **'shape_predictor_68_face_landmarks.dat'** file, where it is required in the code.     
