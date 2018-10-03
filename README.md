# App Engine Node.js Hello World Tutorial
This is a tutorial on how to deploy a Node.js app to App Engine Standard Environment. I chose the standard environment because of its better scaling abilities and scale to zero functionality.

# Steps
1. Create a GCP project in the Google Cloud console
2. Download and install Node.js and the Cloud SDK
    a. Note: If you already have Cloud SDK you will have to switch projects using `gcloud config set project <project-id>`
3. Create a folder and run `npm init` inside and set up `start` to correspond to `node app.js`. 
4. Create an app.yaml file specifying the runtime `runtime: nodejs8`
5. Create a simple Hello World application
6. Run `npm i` to install dependencies.
7. Run `gcloud app deploy`
8. Run `gcloud app browse`

# Clean up
* Go to the projects page and delete project
