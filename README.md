# Detecting Parkinson’s Disease using Machine Learning⚡

![image](https://user-images.githubusercontent.com/70385414/191471540-f4c52f4f-3d82-4338-a930-132a373a963d.png)

<div align="center">
   <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"></img>
   <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green"></img>
   <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"></img>
   <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"></img>
</div>

# IBM-Project-2430-1658471704

Detecting Parkinson’s Disease using Machine Learning
More than 10 million people are living with Parkinson’s Disease worldwide, according to the Parkinson’s Foundation. While Parkinson’s cannot be cured, early detection along with proper medication can significantly improve symptoms and quality of life.

The researchers found that the drawing speed was slower and the pen pressure is lower among Parkinson’s patients. One of the indications of Parkinson’s is tremors and rigidity in the muscles, making it difficult to draw smooth spirals and waves. It is possible to detect Parkinson’s disease using the drawings alone instead of measuring the speed and pressure of the pen on paper. Our goal is to quantify the visual appearance(using HOG method) of these drawings and then train a machine learning model to classify them. In this project, We are using, Histogram of Oriented Gradients (HOG) image descriptor along with a Random Forest classifier to automatically detect Parkinson’s disease in hand-drawn images of spirals and waves.

<div align="center">
<img src="https://lh3.googleusercontent.com/_feL0AG16jhaypq83YLxFfmaY4sg5NURNNngQj4QISnYGl_KaYZN5fAqFXDnIF12TxzZ9LhbOzUskLwcy6DVo-uU5y3Y5hIY4X3283ha7Ugs3g9HHifNMpTDnrIAl5J_voEYvQku"></img>
</div>

# Project Objectives

<h3> By the end of this project:</h3>
<ul >
<li>You’ll be able to understand the problem to classify if it is a regression or a classification kind of problem.</li>

<li>You will be able to know how to pre-process the image by using different data pre-processing techniques.</li>

<li>you will be able to learn how to use OpenCV and machine learning to automatically detect Parkinson’s disease in hand-drawn images of spirals and waves.</li>

<li>You will be able to know how to find the accuracy of the model.</li>

<li>You will be able to build web applications using the Flask framework.</li>
</ul>

# Project Flow

<ol>
 <li> User interacts with the UI (User Interface) to upload the image as input  </li>
 
 <li> The uploaded image is analyzed by the model which is integrated </li>

 <li> Once the model analyzes the uploaded image, the prediction is showcased on the UI and OpenCV window </li>
</ol>

## To accomplish this, we have to complete all the activities and tasks listed below

<ol>

 <li>Data Collection </li>

 <li> Collect the dataset or Create the dataset </li>

 <li>  Image Preprocessing. </li>

 <li> Importing the required libraries </li>

 <li> Loading Train data and Test data  </li>
 
 <li> Quantifying images </li>

 <li> Label Encoding </li>

 <li> Model Building </li>
 
 <li> Training the model </li>

 <li> Testing the model  </li>

 <li> Model Evaluation </li>

 <li> Saving the model </li>

 <li> Application Building </li>

 <li> Create an HTML file </li>

 <li> Build Python Code </li>
</ol>

<div class="Pre-Requisites">
# Pre-Requisites

In order to develop this project we need to install the following software/packages:

# Anaconda Navigator :

Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning related applications. It can be installed on Windows, Linux, and macOS. Conda is an open-source, cross-platform, package management system. Anaconda comes with so very nice tools like JupyterLab, Jupyter Notebook, QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. For this project, we will be using Jupyter notebook and Spyder

To install Anaconda navigator and to know how to use Jupyter Notebook & Spyder using Anaconda watch the video

<a href="https://youtu.be/5mDYijMfSzs" >`https://youtu.be/5mDYijMfSzs`</a>

# To build Machine learning models you must require the following packages

## Numpy:

It is an open-source numerical Python library. It contains a multidimensional array and matrix data structures and can be used to perform mathematical operations

# Scikit-learn:

It is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-nearest neighbours, and it also supports Python numerical and scientific libraries like NumPy and SciPy

# Scikit-image

Scikit-image or skimage, is an open-source Python package designed for image preprocessing.

# Install imutils

Imutils are a series of convenience functions to make basic image processing functions such as translation, rotation, resizing, and displaying Matplotlib images easier with OpenCV

# Open anaconda prompt and type this command

`pip install imutils`

# OpenCV

OpenCV is a library of programming functions mainly aimed at real-time computer vision. Here, OpenCV is used to capture frames by accessing the webcam in real-time.

Open anaconda prompt and type this command

`pip install opencv-contrib-python`

# Flask:

## Web framework used for building Web applications

If you are using anaconda navigator, follow below steps to download required packages:

Open anaconda prompt.

Type `pip install numpy` and click enter.

Type `pip install scikit-image` and click enter.

Type `pip install imutils` and click enter.

Type `pip install scikit-learn` and click enter.

Type `pip install opencv-contrib-python` and click enter.

Type `pip install Flask` and click enter.

</div>

# Project Structure

Let us introduce you to the main project folder downloaded by you in prerequisites.

<img src="https://lh3.googleusercontent.com/TkkONaza7mznm57CxUIlEnng9-kokb5P9lVg3B2jQyXQkzg9Y36Cp4b9BGBHtvQo_75Jsb2rxkVUwFwoMJtQ-3abEbJSYlz2y7rSxMr4sfRMFmuZYgGr5FYXqT3cC9D75Vj4ICKt"></img>

# Training folder contains:

`Parkinson_detect.py`

`model file “parkinson.pkl” `

# Flask App folder contains:

static folder with the style sheets and the image required

templates folder with the HTML pages

app.py, a python script (Flask file) for server side computing.
