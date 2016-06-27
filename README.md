# docker-script 
Install Docker-Engine, Docker-Machine v0.8.0-rc1, Docker-Compose v1.8.0-rc1, Gcloud on Ubuntu with just one terminal command.
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


Note: If you are installing on Ubuntu 14.04 or 12.04, apparmor is required. You can install it using: 
```
apt-get install apparmor
```
