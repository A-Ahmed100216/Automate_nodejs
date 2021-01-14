# End to end Automation
* Create a ci/cd pipeline for the nodeapp.


Task:
Use Jenkins to clone the app and run the tests

Once all the tests passed, Jenkins should trigger build to build docker image and push it your docker hub repo

Create a web-hook on your docker hub repo to send a notification email of success

Next: Jenkins to trigger cd multi-stage docker build to deploy the containerised app on AWS

We have done this with VMs and now it's time to see the real life difference between micro-services-containerisation VS VMs

### Testing CI Pipeline
