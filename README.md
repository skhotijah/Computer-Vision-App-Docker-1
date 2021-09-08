# Computer-Vision-App-Docker

This repository is featured in a 2-part series on Deploying web apps with Streamlit, and Docker.


## Setup instructions

```
$ git clone https://github.com/collinprather/streamlit-docker.git
$ cd streamlit-docker/
$ docker image build -t streamlit:app .
$ docker container run -p 8501:8501 -d streamlit:app
```
Then, the web app will be available at ```http://localhost:8501/```

