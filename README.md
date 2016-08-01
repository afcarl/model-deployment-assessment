# Model Deployment Exercise

## Overview
Deploy a model behind a REST api using (palladium)[https://github.com/ottogroup/palladium] to serve a predictive model via HTTP in real time. You can use the included `iris` example in the palladium repository as your model, though it would be cool to show your own if time allows. The real deliverable here is to see the model served, via Docker. If you deploy to a cloud provider that's also nice (provide the URI to curl if so). Palladium supports R, python and Julia models out of the box.    

If you prefer to roll your own, feel free to not use palladium and instead serve your model behind another web framework using either a JVM based language or python. Your model can be written in any language you please if you go this route and are able to make it work.

## Submission
The goal here is to deliver a Github repo with a `Dockerfile`, model code and web framewrok code. We will clone the repo, and follow instructions in the README to test.

The assumption is that the test will go along the lines of:
- `docker build ...`
- `docker run ...`
- curl ...
- check expected response

