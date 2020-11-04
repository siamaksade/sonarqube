# SonarQube Template for OpenShift 

This is a SonarQube template using the upstream SonarQube images from DockerHub.

To deploy on OpenShift run the following:
```
oc process -f sonarqube-persistent-template.yaml | oc create -f -
```