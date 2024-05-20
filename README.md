# Cat-and-Dog-Classifier-using-Flask-and-Docker

Cat and Dog Classifier using an H5 model. Flask is used to create the web page and Docker to containerize the project.

## Instructions

1. Git Clone repository
2. Run the following commands
   
   ```
   docker image build -t cat-dog-classifier-using-flasl .

   docker run -p 5000:5000 -d flask_docker
   ```
4. Go to http://127.0.0.1:5000/upload in your web browser.

## Resources
H5 model link: https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5

Docker Hub Page: https://hub.docker.com/repository/docker/velvett/cat-dog-classifier-using-flask/general
