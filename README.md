# GCP
Google Cloud Platform Notes

# Basics of Cloud Computing:

## why cloud?
cost of setting up IT infrastructure - huge investment.
Server, switch router, firewall, network, security, storage, etc.
MMC - memory card, if no usage its waste.
Hardware - proper AC room for server, people maintaining them.
**Hypervisor** on top of hardware - instead of OS. it will help in having multiple VMs on the same machine.
Virtualisation - virtual hardware.
Example; VMWare - it helps in giving us the access to multiple VMs installed.
but the hardware should be within reachable i.e. our laptop should be with us so that we can open vmware and access these VMs.

But when we give the access to these VMs on the internet then it becomes the cloud computing where we do not need to be physically present for the hardware to access, all we need is an internet to access them.

Cloud computing is the delivery of computing services 
- servers
- storage
- databases
- networking tool and software over the internet.

  Characteristics of Cloud computing:
  1. On-demand services
  2. Resource pooling 
  3. Elasticity
  4. Broad network access - from any network and device.
  5. Measured services.


### First sample cloud app. hello world deployment for python.
https://first-project-405718.ue.r.appspot.com/


## Important links for GCP certifications
https://www.examtopics.com/exams/google/associate-cloud-engineer/view/9/

## find container IP
docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <container_name_or_id>

## DevOps
WORKDIR does not set the working directory for the rest of the Dockerfile #2282
https://github.com/docker/for-win/issues/2282

