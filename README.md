#Google Cloud + Docker Development Environment Setup Script

####Writeup and commentary dictated into google docs when we did the rest of this guide:
https://docs.google.com/document/d/1aYoDIELLhPqKYOIpYiyrlF_LWctIdsG5SkYtvU6AGLA/edit?usp=sharing

####Requirements:
* GCE Account
* PC or VM Running Ubuntu 16.04
* An hour or so to play with the results.  Note that we're certain that you won't learn anything if you just use the script provided here.  This is here because sometimes, people neeed to do things like this, quickly.  Do the steps step by step, that's how they can stick in your mind.  


* Docker Engine 
* Docker-Machine v0.8.0-rc1
* Docker-Compose v1.8.0-rc1
* Gcloud on Ubuntu with just one terminal command.

It'll ask you for sudo password and Gcloud info, type password for sudo password and Enter for Gcloud info.
Here is the command to run the script:

```
bash docker-script
```
Then close and re-open the terminal window and type:

```
Gcloud auth login
```

To use Gcloud from terminal.

