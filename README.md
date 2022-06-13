# DO180-apps
DO180 Repository for Sample Applications


## Deploying Multi-Container Applications
- SDN enable communication between containers. 
(containers must be attached to the same software-defined network to communicate).

- Podman uses CNI (container network interface) to create SDN 
and attaches containers on the host to that network. 

BuildConfig (BC)
- compile source code, download library dependencies
- package the application as a container image 
- push the image into the registry for the deployment step

Deployment step
- start the pod and making the application available
- only if the build step succeeded. 


