# **Cloud Engineer Assignment: Deploying a Python Flask App on AWS EC2 Using Terraform**

## Time limit

- Assignment needs to be submitted **within 2 days** after it is shared to candidate.

## Objective of the assignment 

- This is to test the basic understanding of candidate's knowledge in the below areas,

1. Programming knowledge on simple API development
2. Git commands usage
3. Knowledge on Containers
4. Testing whether the candidate providing attention to necessary details as part of implementation

## **Problem Statement**

The goal of this assignment is to evaluate your ability to:

1. Develop a **Python Flask application** that returns a simple message.
2. **Containerize** the application using Docker.
3. Automate **AWS infrastructure provisioning** using **Terraform** to:
   - Create an **EC2 instance**.
   - Deploy the containerized Flask application.
   - Expose the application via a public URL.

Step 3: Candidate can use the Cloud provider which they are comfortable with

---

## **Assignment Tasks**

### **1. Develop a Python Flask Application**

- Create a **Flask app** with an endpoint:  
  - `GET /` → Should return `{ "message": "Hello CloudEngine Labs - from Python Flask!" }`
- Create a **Dockerfile** to containerize the application and build the image.
- Push the image to Container registry
- Run the image, and access the endpoint

### **2. Automate AWS Infrastructure Using Terraform**

- Write Terraform code to:
  - Launch an **EC2 instance** (Ubuntu 22.04).
  - Install **Docker** on the instance.
  - Pull the **Docker image** and run the Flask application.

### **3. Deploy & Validate**

- Once the instance is running, access the application via **EC2's public IP** to verify that it returns the expected message.

---

## **Deliverables**

- **GitHub Repository** containing:
  - `app.py` (Flask application)
  - `Dockerfile`
  - URL of the image from container registry
  - `main.tf` (Terraform script)
  - `README.md` with:
    - Instructions to build, deploy, and access the application.
    - Terraform commands to provision and destroy the infrastructure.

---

## **Evaluation Criteria**

- ✅ **Python & Flask Knowledge**: Proper implementation of Flask.
- ✅ **Docker Expertise**: Correct Dockerfile and container execution.
- ✅ **Terraform Proficiency**: Correctly provisioning EC2 and deploying the app.
- ✅ **AWS Knowledge**: Understanding of EC2, security groups, and networking.
- ✅ **Documentation**: Clear and structured README with deployment instructions.

---

### **Bonus Points**

- ✅ Implement **GitHub Actions** to automate image build, push and infrastructure deployment.


---

### How to submit

- Capture the output of **All the Steps** in a _Google Document_ (If you can create the steps in README.md files that is good)
- Clearly mention the steps you have completed in your final documentation
- Share repository link from your GitHub account
- Share the google document link or README file link to [work@cloudenginelabs.io](mailto:work@cloudenginelabs.io)

### Note:

- Anytime if you have questions, please drop a note to [work@cloudenginelabs.io](mailto:work@cloudenginelabs.io)