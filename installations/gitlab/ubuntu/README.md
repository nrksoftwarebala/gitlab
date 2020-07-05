## gitlab install on ubuntu 16+OS

#### the below code have gitlab-ce and gitlab -EE types

* the installtion code installs the latest version of that.


### 1. gitlab CE installation code

```
sudo apt-get install -y curl openssh-server ca-certificates
sudo apt-get install -y postfix 
curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash 
sudo EXTERNAL_URL="http://gitlab.example.com" apt-get install gitlab-ce 

```
* note: /etc/gitlab/gitlab.rb is the main file

gitlab-ctl reconfigure

### 2. gitlab EE installation code

```
sudo apt-get install -y curl openssh-server ca-certificates 
sudo apt-get install -y postfix 
curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.deb.sh | sudo bash 
sudo EXTERNAL_URL="http://gitlab.example.com" apt-get install gitlab-ee 