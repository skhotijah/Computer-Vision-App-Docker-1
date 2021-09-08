# Computer-Vision-App-Docker

This repository is featured in a 2-part series on Deploying web apps with Streamlit, and Docker.

![Navigation](https://user-images.githubusercontent.com/53899191/132553501-9719f0e9-ce8e-46bf-82b5-41a6a9f129be.jpg)




## Setup instructions

```
$ git clone https://github.com/skhotijah/Computer-Vision-App-Docker-1.git
$ cd streamlit-docker/
$ docker image build -t streamlit:app .
$ docker container run -p 8501:8501 -d streamlit:app
```

Then, the web app will be available at ```http://localhost:8501/```

