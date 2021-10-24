## IVP PROJECT | SMART AGRO KIT
Group No- 14

#### Faculty Name-  Dr. Shiv Ram Dubey

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#team-members">Team Members</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>


## About The Project

In modern era many of farmers not able to predict right information due to lack of skills,time This is the reason for many crops failure. Unfortunately the farmers award with huge losses and in some case it grow to be committing suicide.In order to make their task a bit easier we have worked on a project and  developed a reliable and easy to use system for use by farmers. So for detection of diseases on crops we have proposed a smart and efficient technique by using image processing and IoT techniques, farmers need to click pictures of their crops and upload that to our webpage then the system will analyse crops and alerts with disease names as well as how to prevent them.


## Team Members
|   Enrollment No.  |   Name   | Github ID |
|   --------------  |   ----   | -------- |
|    IIT2019239  |  Mrityunjaya Tiwari  | Error404m |
|    IIT2019222  |   Rauank Singh Rathore  |Error404r |
|    IIB2019006  |   Amanjeet Kumar | Amanjeetk11 |
|    IIT2019202  |   JYOTI VERMA |Jyo123-verma |
|    IIT2019236  |  Noonsavath Sravana Samyukta | samyukta9500 |
|    IIT2019200  |   Raj chandra  |RAJCHANDRA |


## Built With
<ul>
   <li>Flask</li>
   <li>Python</li>
   <li>IoT</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>Javascript</li>
  <li>python</li>
</ul>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
  * Create the Virtual Environment
  ```sh
  $ python3 -m venv venv
  ```
  
  * Activate the virtual environment
  ```sh
  $ source venv/bin/activate
  ```
  
  * Install Falsk
  ```sh
  $ pip3 install Flask
  ```
  
  * Install NumPy
  ```sh
  $ python -m pip install numpy
  ```
  
  * Install Pandas
  ```sh
  $ python -m pip install pandas
  ```
  
  * Install Matplotlib
  ```sh
  $ python -m pip install matplotlib
  ```
  
  * Install OpenCV
  ```sh
  $ python -m pip install opencv-python
  ```
  
  * Install Keras
  ```sh
  $ python -m pip install keras
  ```
  
  * Install TensorFlow
  ```sh
  $ python -m pip install tensorflow
  ```
  
 ### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/Amanjeetk11/ivp.git
   ```
2. Change directory to main file
   ```sh
   cd model_codes
   ```
3. Install requirements.txt
   ```sh
   pip install requirements.txt 
   ```
4. Set the FLASK_APP system variable
   ```sh
   $ export FLASK_APP=app.py
   ```
5. Run Flask
   ```sh
   $ flask run
   ```
Visit http://127.0.0.1:5000 to see your app in action 

<!-- Usage -->
## How to use
1.Go through webpage link http://127.0.0.1:5000 
<img src="https://github.com/Amanjeetk11/ivp/blob/main/ss/landing_page.png">

2. Tap on choose file.
3. Upload or click picture of crops.
4. Click on predict

Now system will auto show status of crops ,if disease detected it will shoe name and their cure.

<ul>
   <li>When no disease detected on plant</li>
  <img src="https://github.com/Amanjeetk11/ivp/blob/main/ss/healthy_plant.png">
  
  <li>When no disease detected on plant leafs</li>
  <img src="https://github.com/Amanjeetk11/ivp/blob/main/ss/healthy_plant_leaf.png">
  
  <li>When disease detected on plant</li>
  <img src="https://github.com/Amanjeetk11/ivp/blob/main/ss/dis_palnt.png">
  
  <li>When disease detected on plant leafs</li>
  <img src="https://github.com/Amanjeetk11/ivp/blob/main/ss/dis_plant_leaf.png">
   
</ul>

<!-- Acknowledgements -->
## Acknowledgements
* [Deploy flask app ](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)
* [Flask App tutorial](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)
* [Training model with Tensorflow](https://towardsdatascience.com/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)
* [deploy model using Keras](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)


