# dev_JenksinH7
Jeknisn Development and Configuration for RHEL 7.x

#### Add Jenkins Repo
http://pkg.jenkins.io/redhat-stable/jenkins.repo<br/>

`$sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat-stable/jenkins.repo`<br/>

Import Key<br/>

` $sudo rpm --import http://pkg.jenkins.io/redhat-stable/jenkins.io.key`<br/>

#### Once Installation Completed
Goto http://\<IP Address\>:8080, install plugins and create admin user <br/>
![Init Jenkins](https://github.com/lel99999/dev_JenkinsRH7/blob/master/init_jenkins-02.png) <br/>
![Init Jenkins](https://github.com/lel99999/dev_JenkinsRH7/blob/master/init_jenkins-04.png) <br/>
![Init Jenkins](https://github.com/lel99999/dev_JenkinsRH7/blob/master/init_jenkins-05.png) <br/>
![Init Jenkins](https://github.com/lel99999/dev_JenkinsRH7/blob/master/init_jenkins-06.png) <br/>


  
Install Git, as Jenkins uses git command to pull Github code<br/>

#### Chrome Policy File Ifformation
[Linux Quick Start](https://sites.google.com/a/chromium.org/dev/administrators/linux-quick-start)<br/>

#### Docker Demo
[https://hub.docker.com/r/jenkinsci/pipeline-as-code-github-demo](https://hub.docker.com/r/jenkinsci/pipeline-as-code-github-demo) <br/>

View Log:
```
$docker container ls
$docker logs --details <container_id>
```

