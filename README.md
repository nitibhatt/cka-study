# cka-study
This file is under the works. It will be updated with useful information about CKA

Services:
To expose deployment as a service, use the following command:

kubectl expose deployment/<deployment_name> --port=80 --type=NodePort

Here it is assumed that deployment is created prior to creating a service

An alternative way to create a service is via a YAML file.   

How to find out the IP address of a Ubuntu VM?

curl ipinfo.io/ip
