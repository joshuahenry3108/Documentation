# Deploying a Backend Webservice with database on Revolte

Follow the steps below to deploy your application using the Revolte platform.

---

### 1. Select Existing Project
- Open the Revolte **'Projects'** dashboard.

![image](https://github.com/user-attachments/assets/0d5bb590-9194-4872-97af-4acd71fde844)

- Select the existing project where backend to be deployed. Click on the **'Create Application'** CTA.

![image](https://github.com/user-attachments/assets/729887f2-7020-42e4-859a-e97178ff97b0)

- Enter the following:
  - **Application Name**: `your-application-name`
  - **Repository**: `your-git-repo-url`

![image](https://github.com/user-attachments/assets/e05e06c6-6cfb-40bf-bfa1-7bceb0a3d6a0)

---

### 2. YAML Configuration
- A **YAML Configuration** page will be displayed with preset template selection and YAML editor.
- **Select Environment**: `preview` / `qa` / `staging` / `prod`
- **Select Branch**: `main` / `develop` / `feature/*`

![image](https://github.com/user-attachments/assets/ad9da7ef-b29d-4d7d-94c5-9f9c7b9c4ed7)


- Click on **'Choose Services'**  `Webapp` / `Webservice` / `Webservice+Database` / `Cron` / `Cron+Database` and select the preset as **'Webservice+Database'**.

![image](https://github.com/user-attachments/assets/1f0434aa-e02f-4e4f-91d9-73647f5be91c)

---

### 3. Edit and Commit YAML
- The default YAML will be populated in the editor.

![image](https://github.com/user-attachments/assets/9cdfb41a-d093-4788-bebd-5d08e87a5614)

- Make any necessary changes (e.g., environment variables, branches, services).

![image](https://github.com/user-attachments/assets/bfe1692b-7555-4e04-8426-f9d3995fd33b)

- Enter **Git Commit Message**: `e.g., "Updated deployment config for webapp"`
- Click **Confirm & Proceed**.
- Confirm in the popup to generate a new `revolte.yml` in the repository.

![image](https://github.com/user-attachments/assets/186f963d-5d58-480f-9a35-f65fb4ba7944)

---

### 4. Deploy Application
- Choose:
  - **Environment**: `e.g., preview`
  - **Branch**: `e.g., dev`
- The updated YAML will be visible in the Configuration section.

![image](https://github.com/user-attachments/assets/234d0fc9-0431-4ad1-bce6-c762f2a19514)

---

### 5. Final Deployment
- Click **Confirm & Deploy**.
- If required, add secrets or credentials during the popup by clicking on **Add here** and Click **Confirm** in the confirmation popup.

![image](https://github.com/user-attachments/assets/370faea4-d085-4390-9605-dd07950bd4aa)

- That's it! Deployment will begin and redirects you to the **Runtime Log** for monitoring.

![image](https://github.com/user-attachments/assets/605df2d7-3b15-4d36-ac4b-5c1d91f9a7a3)

---

### 6. Post-Deployment
- Deployment should complete.

![image](https://github.com/user-attachments/assets/4225af61-126e-44ae-8455-05bec61c7ded)

Revolte will now provision a new project with all services and configurations that were defined in the template.

- The page will get redirect to the **Overview** to view **Health Status**, **Application URL**, **Active Instances**

![image](https://github.com/user-attachments/assets/bbb90bc2-24f7-4e15-9af7-5c58618aec20)

---

> ✅ You’ve now deployed your app using Revolte!
