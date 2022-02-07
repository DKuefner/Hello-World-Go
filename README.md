# Hello-World-Go
Hello World app for GCP Cloud Run

This app provides the following:

- Web page displaying a simple Hello World message
- Using Git and Git Hub as code repository
Google Cloud Build as CI/CD engine which allows versioning (cloudbuild file required)
- Cloud Run as PaaS service
- The app written in Go (based on a community example)

The app is intended to be deployed on Google Cloud Run. The cloudbuild.yaml in this example contains the links to an existing Cloud Repository. Feel free to clone the repository from https://github.com/DKuefner/Hello-World-Go.git and sync it with your own GitHub repo. Then connect your Cloud repository with your GitHub repository. The links in cloudbuild.yaml should be replaced with your own Google Cloud repo links.
