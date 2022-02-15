# CI and Jenkins
Jenkins can be used for continous testing of new code, alongside other tools it can make the CI pipeline a lot faster. 
## Webhooks setup
Setting up a webhook allows Github to trigger Jenkins to start a new build whenever a new commit is pushed. In order to set one up you need to:
- Go to the Github repository that is linked to Jenkins, go to settings and click on webhook and then add webhook.
- For the payload URL add the url of jenkins (specifically the IP and port) with /github-webhook/ appeneded at the end. for example http://12.345.678.90:8080/github-webhook/
- Choose json as the content type, send me everything, and active

## Creating CI job in jenkins
- Create a new ratio 
