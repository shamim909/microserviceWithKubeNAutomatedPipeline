DevOps CI CD with toolset setup and configuration, Static code analysis, build, containerization, antifactory, smoke test,  automated regression, deploy in Kubernetes  



1.	Gitlab install & configuration 
a.	Install as pod using helm
i.	Install helm
    Sudo curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
ii.	Install gitlab ce

iii.	
b.	Add CentOS-7 Gitlab repo
sudo curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.rpm.sh | sudo bash

c.	Install
sudo yum -y install gitlab-ce
 
d.	Configure 
Edit: sudo vim /etc/gitlab/gitlab.rb

 
e.	Apply configuration
sudo gitlab-ctl reconfigure

f.	Access gitlab using external URL I,e http://localhost/gitlab and create a new password for root user then login to gitlab
 

2.	Create a project in gitLab
