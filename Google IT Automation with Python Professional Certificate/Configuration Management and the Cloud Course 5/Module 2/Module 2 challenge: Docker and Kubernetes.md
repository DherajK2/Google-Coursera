# Module 2 challenge: Docker and Kubernetes

1. **Question 1**  
Another developer asked where the central repository is for downloading containers. What should you tell them?  
- [x] Docker Hub  
- [ ] Docker Host  
- [ ] Docker Repo  
- [ ] Docker Central  

2. **Question 2**  
You explain to another programmer that it is typical for a Docker image to be composed of up to a dozen layers. What is the purpose of having multiple layers?  
- [ ] To store your data on separate layers  
- [ ] To make it easier to debug your program  
- [ ] To allow a different programmer to edit the code in different layers  
- [x] To keep the final images as small as possible  

3. **Question 3**  
You informed another programmer that Cloud Run can help them launch containers. They asked what the benefit is of using Cloud Run. What should you tell them?  
- [x] It allows you to deploy code written in any programming language if you can put the code into a container.  
- [ ] It allows you to run an application in the background continuously.  
- [ ] It allows you to reuse multiple containers at once for different programs.  
- [ ] It allows you to assign it to a static IP address so that it can be accessed from anywhere.  

4. **Question 4**  
You are developing a Python-based data processing application. One component of the application processes raw data, while another component analyzes the processed data. You want these components to easily exchange data. You also want to ensure that the processed data persists even if one of the containers restarts. Why are Pods in Kubernetes a good fit for this task? Select all that apply.  
- [x] Pods enable data sharing.  
- [x] Pods facilitate co-location.  
- [x] Pods simplify inter-container communication.  
- [x] Pods share the same network namespace.  

5. **Question 5**  
Samantha, a lead developer, is explaining to her team how Kubernetes Deployments work. She mentions that Deployments use a specific resource to ensure the desired number of identical Pods are always running, even if some Pods fail or are deleted. What resource is Samantha referring to?  
- [ ] Service  
- [x] ReplicaSet  
- [ ] ConfigMap  
- [ ] PersistentVolumeClaim  

6. **Question 6**  
You’re setting up a Kubernetes cluster for a small application that you don’t plan to offer to the general public. It’s time to choose the machine type for your nodes. Which of the following is probably the best choice?  
- [x] A general-purpose machine  
- [ ] A compute-optimized machine  
- [ ] A memory-optimized machine  
- [ ] An accelerator-optimized machine  

7. **Question 7**  
You just got a new job in the IT department of a software firm. You overhear two of your new colleagues talking about the organization’s local development cluster. What do you think this cluster might be used for? Select all that apply.  
- [x] Application development and testing  
- [x] Rapid iteration and debugging of applications before deploying them to production clusters  
- [ ] Data storage to comply with data governance requirements  
- [ ] To support low latency, particularly in zones with poor network connectivity  

8. **Question 8**  
You’ve decided to run your Docker containers on the Google Cloud Platform, and you’re about to choose which service to use. What are some advantages of Cloud Run?  
- [x] It’s a fully managed platform  
- [ ] It can accommodate stateful applications.  
- [x] It can scale down to zero.  
- [ ] It has a huge amount of flexibility in its configuration.  

9. **Question 9**  
Which of the following is the best phrase to complete this sentence? Containers allow users to _____________________.  
- [ ] run an application code one line at a time.  
- [ ] quickly dissect an application for troubleshooting purposes  
- [ ] preview an application before downloading it.  
- [x] run an application using a snapshot of the programmer’s system.  

10. **Question 10**  
Carlos is deploying a Python application in a cloud environment. The application has a user interface that he expects will experience heavy traffic from users around the world. Additionally, he's integrating a third-party payment gateway. Which Kubernetes service types should Carlos consider for these components? Select all that apply.  
- [ ] ClusterIP  
- [x] LoadBalancer  
- [x] NodePort  
- [ ] ExternalName  
