# DevOps-project-101
Tech Stacks Used - Linux, Docker, Git, Jenkins, and Kubernetes

The task involves containerizing a Node.js web application using Docker, setting up a CI/CD pipeline using Jenkins, and deploying the application to a Kubernetes cluster running on your local system or on the cloud if it's possible.

Scenario
You are a DevOps Engineer at a software development company that has developed a Node.js web application. You need to containerize the application using Docker, set up a CI/CD pipeline using Jenkins, and deploy the application to a Kubernetes cluster running on your local system.

Requirements
1. You should have a local Kubernetes cluster running on your system. Install a local Kubernetes cluster such as Minikube or Kind on your system.
Once you have set up the local Kubernetes cluster, you should be able to interact with it using the kubectl command line tool.
2. You should use Docker to containerize the Node.js application.
3. You should use Git to manage the source code of the application.
4. You should use Jenkins Pipeline to automate the build and deployment process of the application to the Kubernetes cluster.
5. You should use Kubernetes to deploy and manage the application.

Tasks
1. Create a GitHub repository.
2. Clone the repository to your local system.
3. Write a Dockerfile for the Node.js application.
4. Build a Docker image of the application and push it to a Docker registry.
5. Write a Kubernetes deployment manifest for the application.
6. Write a Kubernetes service manifest for the application.
7. Set up a Jenkins job to automate the build and deployment process of the application to the Kubernetes cluster.
8. Configure the Jenkins Pipeline job to pull the source code from the Git repository, build the Docker image, push the image to the Docker registry, and deploy the
application to the Kubernetes cluster.

9. Verify that the application is running correctly on the Kubernetes cluster.
Submission

You should submit the following:
The URL of your GitHub repository along with a folder named deliverables with
following items.
1. The Dockerfile used to build the Docker image of the Node.js application.
2. Screenshots or logs showing that the Docker image was built and pushed to a Docker registry.
3. The Kubernetes deployment manifest for the application.
4. The Kubernetes service manifest for the application.
5. Screenshots or logs showing that the application was deployed and is running correctly on the Kubernetes cluster.
6. Jenkinsfile used to automate the build and deployment process of the application.
7. Any other relevant documentation or notes about your implementation.
Good luck!
