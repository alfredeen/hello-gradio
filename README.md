# hello-gradio
A simple Gradio example.

## Trunk based workflow
In this repo, we work [Trunk based](https://www.toptal.com/software/trunk-based-development-git-flow), which means that we bypass the dev branch.

## Begin

If not already in the project folder, open a terminal and navigate there

    cd ./hello-gradio

## Build and run a docker image locally

    docker build -t hello-gradio:dev .

## Setup and run locally

Create and set the virtual environment

    pyenv virtualenv 3.12.2 hello-gradio-3.12.2
    pyenv local hello-gradio-3.12.2

Install gradio for local development

    pip install gradio

Run the Gradio app

    gradio main.py

Browse the app at  http://localhost:8080
