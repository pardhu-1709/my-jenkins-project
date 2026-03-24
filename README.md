# My-Jenkins-Project

This project demonstrates **building and deploying artifacts using Jenkins**, and storing them in **AWS S3**.  
It shows how a web application can be automatically built, deployed on **Tomcat**, and backed up to S3.

---

# My Project

## Project Overview
- **Build Automation:** I use Jenkins pipelines to automatically build my project.  
- **Artifact Deployment:** The `.war` artifact is deployed directly to my Tomcat server.  
- **S3 Storage:** The artifact is backed up and distributed via AWS S3.  

---

## Architecture

### 1️⃣ Application Path
![Application Path](https://github.com/pardhu-1709/my-jenkins-project/blob/main/application%20path.png)  
*Shows the project folder structure and application flow.*

### 2️⃣ Jenkins Build Status
![Build Status](https://github.com/pardhu-1709/my-jenkins-project/blob/main/build%20status.png)  
*Shows the Jenkins job build status.*

### 3️⃣ Deploy Artifact
![Deploy Artifact](https://github.com/pardhu-1709/my-jenkins-project/blob/main/deploy%20artifact.png)  
*Deployment of artifact to Tomcat server.*

### 4️⃣ Alternative Deployment View
![Deploy Artifact1](https://github.com/pardhu-1709/my-jenkins-project/blob/main/deploy%20artifact1.png)  
*Alternative view of deployment steps.*

### 5️⃣ Application Running
![Application Runs on Web](https://github.com/pardhu-1709/my-jenkins-project/blob/main/application%20runs%20on%20web.png)  
*Shows the application running on the web after deployment.*

### 6️⃣ Tomcat Server Running
![Tomcat Server Running](https://github.com/pardhu-1709/my-jenkins-project/blob/main/tomcat%20server%20running.png)  
*Tomcat server is running and serving the application.*

### 7️⃣ Artifact Stored in S3
![S3](s3.png)  
*Artifacts are stored in AWS S3 bucket.*

---

## Cicd Pipeline Implimentation using Jenkins, Tomcat and Aws S3
1. Configure Jenkins and create a pipeline.
2. Connect to GitHub repository to Jenkins.
3. Build the project using the Jenkins job.
4. Deploy the artifact to Tomcat server.
5. Check the application running on web browser.
6. Confirm the artifact is saved in S3.

---

## Notes
- Ensure AWS credentials are configured in Jenkins to allow S3 access.
- Tomcat must be running and reachable for deployment.

---

<div style="border-top:3px solid #4CAF50;"></div>
