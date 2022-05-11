# SRE-Documentation
Documentation hub for the SRE team

## Start-up
The Frontend developed using [AngularCLI](https://angular.io/guide/setup-local). The Backend developed using Spring and Java.

Bubble is a social media application, that allows users to sign up for free and create accounts. Once logged in, users can search and add friends as well as create a group with certain people in your friends list. Users can share post: which include normal text, pictures and/or videos. Users are also able to see what their friends' are posting and reply to the post with a comment. These features and overall project were made possible by previous batches. The second batch, Full Stack Java and Angular, were responsible for creating the major functionalities of the application. While Bubble3, the third batch, added to the application through additional user stories. 

We are the fourth batch to be working on this application, while the other batches worked on the actual development side of the application. We were tasked to take this full stack application and apply SRE principles. This included developing a Jenkins pipeline to Continuosly Integrate, Deliver and Deploy our code. The deployment to the cloud allowed for the application to be constantly monitored, making sure our SLIs are being recorded to ensure SLOs are being met.

## Installations
* Java
   * Install [Java](https://www.java.com/en/download/manual.jsp)
   
* Angular 4
  * Install [NodeJS](https://nodejs.org/en/)
  * Install the CLI using the npm package manager:
     > npm install -g @angular/cli@12
* Terraform 
  * Getting Started: (https://learn.hashicorp.com/collections/terraform/aws-get-started)
  * Use Terraform to build Infrastructure: (https://learn.hashicorp.com/tutorials/terraform/aws-build?in=terraform/aws-get-started)
* Jenkins
  * Install Jenkins: (https://www.Jenkins.io/doc/book/installing/kubernetes)
* Helm/Chart Installations
  * Prometheus/Prometheus Adapter/Metrics API
     * repo: helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
  * Grafans Stack (Grafana, Loki, Promtail)
     * repo: helm repo add grafana https://grafana.github.io/helm-charts
     * chart: helm install my-release grafana/grafana
    

## Incident Management
  * Document with how we would go about handling an incident (Incident Management Playbook) [https://docs.google.com/document/d/18YN_ZnKWlmu27GWWKfjPXXLTtFM98XueBnxvGu8mVAw/edit]
## Post Mortem 
  * Document with our Post Mortem with further details on the incident, what was done to be resolved and possible ways to prevent from incident happening       again
[https://docs.google.com/document/d/1TAgcGVKNex5euM2TDOpZWnAPuvY2TMneBER6vmayjMs/edit]
