## About

Template to be deployed to Google App Engine via CircleCI when swagger.yaml is pushed.

## Usage

1. Fork this repo
* Connect forked repo to CircleCI
* Set Environment Variables in CircleCI 
    * GOOGLE_COMPUTE_ZONE: Google Cloud Zone
    * GOOGLE_PROJECT_ID: Google Cloud Project ID
    * GCLOUD_SERVICE_KEY: Google Cloud service account json
* Update swagger.yaml and push
* It builds with CircleCI and deploys to Google App Engine.
