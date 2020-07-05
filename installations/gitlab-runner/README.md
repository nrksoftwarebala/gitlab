## gitlab runner installation for Ubuntu 16 +os

```
sudo curl -o script.deb.sh https://packages.gitlab.com/install/repositories/runner/gitlab-runner/script.deb.sh
sudo chmod +x script.deb.sh 
sudo ./script.deb.sh
sudo apt-get install -y gitlab-runner
```
sudo gitlab-runner register    ---> to register runner with gitlab
