(Please use the discussions page for questions/comments/etc.)

This repo contains the code needed to run Puppeteer on Lambda with a Docker Container. Just build and tag the image, upload to ECR, create a new lambda function with the image with an API Gateway (HTTP), and in the lambda console choose the latest image for deployment.