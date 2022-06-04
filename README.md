# yaml-actions

This is intended to be a storage for useful YAML files for both testing and deployment in multiple languages and to different services.

Several of these require inputs from within the YAML files to correctly run and deploy.

Currently all set to trigger on push and/or pull request to "main".

All rights to respective copyright owners.

## Deployment

Currently 3 deployment YAML:
- GCP Cloud Run (REQUIRES VARIABLES)
- Docker build (REQUIRES VARIABLES)
- Firebase (REQUIRES VARIABLES)

## Testing

- Java Maven
- NodeJS (Vers. 16.x)
- Python with Anaconda packaging
- Python pytest only

## Future plans

- GCP Cloud Functions deployment
- Azure deployment
- Java gradle testing
- Triggering GCP Cloud Function for testing when deploying to GCP