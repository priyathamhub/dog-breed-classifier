
# Dog Breed Classifier Capstone Project

## Project Overview

This project aims to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, our algorithm identifies an estimate of the canine’s breed.  If supplied an image of a human, the code identifies the resembling dog breed. 

![Screenshot 2020-10-23 181443](https://user-images.githubusercontent.com/58246016/97005224-c9655280-155b-11eb-9a50-8bac8dd288d1.png)
![Screenshot 2020-10-23 181522](https://user-images.githubusercontent.com/58246016/97005230-cb2f1600-155b-11eb-8b75-501be20edc2f.png)


Along with exploring state-of-the-art CNN models for classification and localization, this project aims to highlight the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. 

To get a better understanding of the project, you may read the [Project Report](https://github.com/priyathamhub/dog-breed-classifier/blob/main/Capstone_Report.pdf).

## Dependencies

This project mainly makes use of Python, Jupyter Notebooks, OpenCV and PyTorch. Other packages used in this project have been listed in the `requirements.txt` file and may be installed following the instructions in the Project Instructions section.

## Project Instructions

To manually run through the code, you may either follow the instructions given below to run the code locally, or you may simple follow this URL to open the notebook on Google Colab: https://bit.ly/3hFjpC3

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/priyathamhub/dog-breed-classifier.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
   
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Install the necessary Python packages

   ```
   pip install -r requirements.txt
   ```

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

  ```
  jupyter notebook dog_app.ipynb
  ```

---

> This project was submitted as the Capstone Project for the Machine Learning Engineering Nanodegree Program at Udacity
