# Helm_to_deploy_nginx

This is a simple Helm chart which:
  - Creates deployment for nginx.
  - Creates a service to expose this deployment.
  - Creates a Configmap which stores helloworld.html.
  - Mounts the Configmap into a container.
  - As a result, nginx will serve the helloworld.html.

To install the Helm chart, simply use one of the following methods:
  1. install the Helm chart directly by typing the following command to your terminal:
        helm install helloworld https://github.com/MohammedRDallasheh/Helm_to_deploy_nginx/blob/main/helloworld-0.1.0.tgz?raw=true
  2. clone the git repository by: git clone https://github.com/MohammedRDallasheh/Helm_to_deploy_nginx.git
      and then install the Helm chart by navigating to the cloned directory in your terminal and then typing the following command:
        helm install helloworld helloworld-0.1.0.tgz 
        
To check that nginx serves the right page, follow the printed commands that will be printed after you install the Helm chart. go to the printed URL, and check the served page.

