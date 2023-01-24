# This one is use for create a k8s cronjob and auto refresh aws ecr token
- Currently aws ecr token will auto expired after 12 hours. We need to create a cronjob that will run every 3 hours to refresh and update it in secret manager.


### Dockerfile