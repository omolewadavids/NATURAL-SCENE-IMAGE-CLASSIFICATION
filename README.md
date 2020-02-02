## NATURAL-SCENE-IMAGE-CLASSIFICATION

### Objective:
My objective is to build a powerful Neural Network that can classify natural scene images into 6 categories. {'buildings' -> 0, 'forest' -> 1, 'glacier' -> 2, 'mountain' -> 3, 'sea' -> 4, 'street' -> 5 } with more accuracy using CNN with a lot of hyper-parameter tunning and transfered learning. The Model will be trained in **AWS SageMaker studio** development environment

  ### Data Source
  This data was initially published on [DataHack](https://datahack.analyticsvidhya.com) by Intel to host a Image classification Challenge.

### Requirement:
* AWS Account

### Creating all AWS Resourses needed to Create, Train and Deploy the Machine Learning Model
* [Step 1](#Create-an-Amazon-S3): Create an Amazon S3 Bucket for storing the Training Image Datasets and the Model Artifacts 
* [Step 2](#Create-an-Amazon-SageMaker): Create an Amazon SageMaker Notebook Instance that will run the Jupyter Notebook
* [Step 3](#Data-Source): Download the Dataset from [DataHack](https://datahack.analyticsvidhya.com), Explore, and Transform the Training Data and upload to Amazon S3 bucket
* [Step 4](#Training-the-Model): Train the Model using the provided training script **Natural_Scene_Image_Classification.ipny**   
* [Step 5](#Model-Deployment): Deploy the Model to Amazon SageMaker
* [Step 6](#Model-Validation-and-Integration): Validate the Model and Integrate the SageMaker Endpoints into Internet-facing Applications
* [Step 7](#Clean-up): Clean Up by deleting the Endpoint

Follow the sagemaker script for the process
