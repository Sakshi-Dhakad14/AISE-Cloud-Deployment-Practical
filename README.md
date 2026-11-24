# ☁️ Cloud Deployment, Monitoring & AI in DevOps

## 📌 Project Overview

This project demonstrates the process of building, testing, and deploying a web application using Streamlit and GitHub. It is developed as part of the **AI-Enabled Software Engineering – Unit 5 Practical**.

The application is built using Python and Streamlit, tested locally, uploaded to GitHub, and deployed on Streamlit Community Cloud.

The practical also covers cloud deployment, deployment monitoring, troubleshooting, CI/CD concepts, and the role of AI in DevOps.

## 🎯 Objectives

- Understand local hosting and cloud hosting.
- Build an interactive web application using Streamlit.
- Understand the purpose of `requirements.txt`.
- Upload source code to GitHub.
- Deploy an application using Streamlit Community Cloud.
- Verify the application through a public URL.
- Understand deployment logs and troubleshooting.
- Learn CI, Continuous Delivery, and Continuous Deployment.
- Understand AI applications in DevOps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Web application framework |
| Git | Version control |
| GitHub | Source code management |
| Streamlit Community Cloud | Cloud deployment |
| VS Code | Code editor |

## 📂 Project Structure

```text
AISE_Cloud_Deployment_Practical/
│
├── app.py
├── requirements.txt
└── README.md
```

## 💻 Application Features

- Displays the application title and description.
- Accepts user input through a text box.
- Provides a Submit button.
- Displays a personalized success message.
- Shows a warning when the input is empty.
- Includes a deployment verification section.

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Sakshi-Dhakad14/AISE-Cloud-Deployment-Practical.git
```

### Step 2: Navigate to Project Folder

```bash
cd AISE-Cloud-Deployment-Practical
```

### Step 3: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python -m streamlit run app.py
```

The application will open locally at:

```text
http://localhost:8501
```

## ☁️ Cloud Deployment

The application is deployed using Streamlit Community Cloud.

### Deployment Steps

1. Create a GitHub repository.
2. Upload `app.py` and `requirements.txt`.
3. Open Streamlit Community Cloud.
4. Sign in using GitHub.
5. Select the project repository.
6. Select the `main` branch.
7. Set the main file path to `app.py`.
8. Click Deploy.
9. Wait for the application to become available.
10. Open and verify the public application URL.

**Deployment Platform:** Streamlit Community Cloud

**GitHub Repository:**  
https://github.com/Sakshi-Dhakad14/AISE-Cloud-Deployment-Practical

**Live Application:**  
Add your actual Streamlit public URL here.

## 🔄 Git and GitHub Commands

The following commands were used to upload and update the project:

```bash
git init

git add app.py requirements.txt

git commit -m "Add cloud deployment demo"

git branch -M main

git remote add origin https://github.com/Sakshi-Dhakad14/AISE-Cloud-Deployment-Practical.git

git push -u origin main
```

To push future updates:

```bash
git add .
git commit -m "Update application"
git push
```

## 🔍 Deployment Verification

The deployed application can be verified using the following checks:

1. Open the public application URL.
2. Check whether the application title is visible.
3. Enter a name in the input field.
4. Click the Submit button.
5. Verify the success message.
6. Submit without entering a name.
7. Verify the warning message.

Deployment is considered successful when the hosted application loads and its interactions work correctly.

## 🐛 Deployment Troubleshooting

| Error | Possible Solution |
|---|---|
| ModuleNotFoundError | Check `requirements.txt` |
| Wrong entry point | Verify that the main file path is `app.py` |
| SyntaxError | Check the indicated line in the Python code |
| Application not loading | Check deployment logs |
| Update not visible | Verify GitHub commit and deployment status |
| Works locally but fails in cloud | Check dependencies, Python version, file paths and logs |

## 🤖 AI in DevOps

AI can improve DevOps processes through:

### 1. Log Analysis
AI can summarize deployment logs, identify errors, and highlight unusual patterns.

### 2. Predictive Monitoring
AI can analyze metric trends and identify patterns that may indicate potential system issues.

Example CPU utilization:

```text
35% → 42% → 55% → 67% → 82% → 94%
```

Traditional monitoring generally triggers alerts when a configured threshold is crossed, whereas predictive monitoring can identify increasing trends earlier.

### 3. Deployment Troubleshooting
AI can explain error messages and suggest possible solutions. Engineers must verify the suggested fixes.

### 4. Workflow Optimization
AI can help identify slow processes, repeated tasks, and bottlenecks in software development workflows.

### 5. Infrastructure Automation
Automation tools and configuration files help create and configure infrastructure consistently.

## 🔁 CI vs Continuous Delivery vs Continuous Deployment

| Concept | Meaning |
|---|---|
| Continuous Integration (CI) | Code changes trigger automated builds and tests. |
| Continuous Delivery | Software is built, tested, and kept ready for release. Production release may require approval. |
| Continuous Deployment | Every qualifying change is automatically released to production without manual approval for each successful change. |

## 📚 Learning Outcomes

Through this practical, I learned:

- How to create and run a Streamlit application.
- How to manage dependencies using `requirements.txt`.
- How to use Git and GitHub for source code management.
- How to deploy a Python application on Streamlit Community Cloud.
- How GitHub updates trigger cloud redeployment.
- How to verify and troubleshoot cloud applications.
- How AI can support monitoring and DevOps workflows.

## 👩‍💻 Author

**Sakshi Dhakad**

B.Tech – Computer Science and Engineering

Jaypee University of Engineering and Technology (JUET), Guna

---

⭐ This project was developed as part of the AI-Enabled Software Engineering – Unit 5 Practical.
