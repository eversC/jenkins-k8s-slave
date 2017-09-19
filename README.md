# DEPRECATED
jenkins master now unpacks the apache-maven binary into slaves when it's used

# jenkins-k8s-slave

FROM [gcr.io/cloud-solutions-images/jenkins-k8s-slave](https://console.cloud.google.com/gcr/images/cloud-solutions-images/GLOBAL/jenkins-k8s-slave)

apt-get install:
* maven + dependencies
