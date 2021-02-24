# Building a Pytorch Lightweight Pipeline

Learn how to build a pytorch pipeline in a few steps

  1. Install docker and push base images used
  
      a. `sudo snap install docker --classic`
      
      b. `docker pull python:3.7.1`
      
      c. `docker pull pytorch/pytorch:latest`
  
  2. Install and Import libraries - kfp and pip
  
  3. Write a python function for each step in your ML workflow
  
      a. Obtain_data Function
      
      b. Preprocess_data Function
      
      c. Train_tensorflow Function
      
      d. Predict_tensorflow Function  
      
  4. Create Kubeflow components for each step from the python functions defined above 
  
  5. Define and Compile Kubeflo Pipeline
  
  6. Upload the Pipeline

Find a visuall walkthrough on how the Tensorflow Lightweight Pipeline is built [here](https://drive.google.com/file/d/1ViY5o5GqR2T8TAIfsNJSVnpTtsz0wS_s/view?usp=sharing).