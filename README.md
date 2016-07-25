# rancher-jenkins-startup-scripts

This container is inspired by other rancher images. It's a confd based container that will create some configuration scripts (loaded at startup by jenkins).
This container is already configured (in the base image) to connect to the rancher api to get the metadata and do the templating of configuration file.

It will configure jenkins security by creating one account for the project (given from the UI when you create the stack).
