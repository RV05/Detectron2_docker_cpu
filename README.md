# Detectron2_docker_cpu 
created a flask web app running inside a docker container with nginx+uwgsi configurations for load balancing that takes 5 images from the test folder inside the S3 bucket from AWS and applies the AI model for bird dropping and flash detection and returns the class number and confidence score of the class detected. Exception handling takes care of the corrupted files.


#Deployment-using-nginx-wgsi
Used boto3 to get images from S3 bucket in AWS
