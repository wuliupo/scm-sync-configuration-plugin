SCM Sync configuration plugin
=============================

Jenkins/Hudson scm-sync-configuration plugin

##[Introduction](https://wiki.jenkins-ci.org/display/JENKINS/SCM+Sync+configuration+plugin)

Syncs configuration files to a SCM repository and tracks changes done to them

1. Keep sync'ed your config.xml (and other ressources) jenkins/hudson files with a SCM repository
2. Track changes (and author) made on every file with commit messages

##Dependencies

[Jenkins Subversion plugin](https://wiki.jenkins-ci.org/display/JENKINS/Subversion+Plugin)

##Configuration
To verify that the plugin is well installed, go to the Administration panel, then in the "System configuration" section : you should notice a "SCM Sync Configuration" section:

![Configuration](https://wiki.jenkins-ci.org/download/attachments/46336078/Jenkins+-+scm-sync-configuration+-+Enter+your+synchronized+SCM2.png?version=1&modificationDate=1374219414000)

##Usage
Once initialized, every time you'll submit a configuration view that can be sync'ed by the SCM Sync Configuration plugin, you'll be prompted for a comment that will be put on the commit message on your SCM Repository.

![Usage](https://wiki.jenkins-ci.org/download/attachments/46336078/Jenkins+-+scm-sync-configuration+-+Comment+prompt2.png?version=1&modificationDate=1374219411000)

##Logs
On every pages, you will have some scm sync config status at the bottom of the page, saying if something went wrong:

![Logs](https://wiki.jenkins-ci.org/download/attachments/46336078/Jenkins+-+scm-sync-config+-+Display+Status.png?version=1&modificationDate=1374219622000)

More can be seen in system log,

![more](https://wiki.jenkins-ci.org/download/attachments/59512165/JenkinsSystemLogger.jpeg?version=1&modificationDate=1330726151000)

More information on [Jenkins wikipage](https://wiki.jenkins-ci.org/display/JENKINS/SCM+Sync+configuration+plugin)
