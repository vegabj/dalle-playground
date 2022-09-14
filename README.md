# DALL-E Playground

This repository was used as a showcase for students by running the backend on a cloud platform and letting students try different prompts.


## Local usage

1. Make sure you have [docker](https://docs.docker.com/get-docker/) and [The NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html) installed 
2. Clone or fork this repository
3. start server `docker-compose up`, add `-d` to `docker-compose up` if you'd like to run it in the background
4. The first time will take some time to download the images, models and other dependencies. 
   models and other dependencies are downloaded only once, and then cached.
4. Copy backend's url from step 2 and paste it in the backend's url input within the web app.
   
   webapp at `http://localhost/dalle-playground`

## Acknowledgements

A playground for DALL-E enthusiasts to tinker with the open-source version of
OpenAI's [DALL-E](https://openai.com/blog/dall-e/), based on [DALL-E Mini](https://github.com/borisdayma/dalle-mini).

This repo is forked from [saharmor](https://github.com/saharmor/dalle-playground).
Which again is a full-stack flavour of [Boris Dayma's](https://github.com/borisdayma) DALL-E Mini
repository. 
