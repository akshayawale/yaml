############################################## KEY   POINTS  TO RUN THIS  PROJECT #########################################

DEPLOY NODEJS APPLICATION ON AN EC2 INSTANCE 
CREATE DOCKERFILE ON SAME EC2 WHERE YOU HAVE HOSTED NODEJS APPLICATION
CREATE TERRAFORM CONFIGURATION FILES ON ANOTHER EC2 INSTANCE
CREATE A CENTRAL REPOSITORY
UPLOAD NODEJS FIELES AND DOCKER FILE TO THIS REPO.
IN THIS SAME REPO CREATE  A FOLDER FOR TERRAFORM AND UPLOAD .TF FILES IN THIS FOLDER
IN THIS SAME REPO GOT TO ACTIONS CREATE NEW GITHUB ACTIONS WORKFLOW /DEPLOY.YML
IN THIS DEPLOY.YML WRITE A CICD PIPELINE

REMEMBER THIS KEY POINTS TO MAKE SURE YOUR CICD GO's  WELL 
GO TO DOCKERHUB CREATE A PERSONAL TOKEN                          ######### USE THIS AS PASSWORD ALTERNATIVE FOR DOCKER
GO TO GITHUB SETTINS/DEVELOPER OPTIONS AND CREATE A PASSWORD TOKEN   ########### USE THIS AS PASSWORD ALTERNATIVE FOR GITHUB
GO TO BRANCH SETTINGS  CREATE A SEPERATE SECRET FOR DOCKERHUB USERNAME DOCKERHUB PASSWORD AND AWS ACCESSKEY AND AWS SECRET KEY  
IF YOUR WORKFLOW IS NOT RUNNING CHECK THE FILE PATH IT SHOULDBE GITHUBNAMENAME/GITHUB REPO:-NAME:-YAML/.GITHUB ACTIONS/WORKFLOWS/.DEPLOY.YML
