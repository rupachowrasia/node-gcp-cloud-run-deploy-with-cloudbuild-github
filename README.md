# Deploy node.js app in Google Cloud Run using Cloud Build and Github

> This project demonstrate how to deploy node.js sample app in Google Cloud Run using Cloud Build and Github

## 🚀 Features

- ✨ Google cloud acount setup
- ⚡ Cloud Run
- 🔒 How to deploy node app from local

## 🛠 Tech Stack

- Node.js
- Express
- Google Cloud(Cloud Run)

## 🧑‍💻 Local Setup
- Create free account in google cloud if not already have
- Login to Google cloud console, create a new project, or can use existing one
- Link billing account to project if not already linked
- Install and setup google cloud cli(Google cloud sdk) in local as per OS
- Create simple node.js app in local
- Enable Cloud Run Admin API and Cloud Build API, if not already enabled
- In Google Cloud Console select Cloud Run, Create Service, setup with cloud build(select repo, build type select Dockerfile) and create service in any region as per your choice
- Prepare Dockerfile and cloudbuild.yaml file in node app’s root folder
- When you push to GitHub, app will be deployed to Cloud Run

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/rupachowrasia/gcp-cloud-run-deploy-with-cloudbuild-github-using-nodejs.git

# Move into the project directory
cd gcp-cloud-run-deploy-with-cloudbuild-github-using-nodejs

# Install dependencies
npm install

# Run the app
npm run start
