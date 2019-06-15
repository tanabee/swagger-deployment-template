## About

This is a template where push swagger.yaml will deploy a Swagger server to Google App Engine through CircleCI.

## Usage

1. Fork this repo
2. Connect forked repo to CircleCI
3. Set Environment Variables in CircleCI 
    * GOOGLE_COMPUTE_ZONE: Google Cloud Zone
    * GOOGLE_PROJECT_ID: Google Cloud Project ID
    * GCLOUD_SERVICE_KEY: Google Cloud service account json
4. Update swagger.yaml and push
5. It builds with CircleCI and deploys to Google App Engine.
