# Deploying a Backend Webservice with database on Revolte

Follow the steps below to deploy your application using the Revolte platform in existing project.

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
- The default YAML for Webservice with Database will be populated in the editor.

![image](https://github.com/user-attachments/assets/061c6b8c-84af-422e-b7eb-b4c970882627)


- Make any necessary changes (e.g., environment variables, branches, services, port, database variables).

![image](https://github.com/user-attachments/assets/0adc754b-3cc1-45b1-b84c-fb66a7c44c94)


- Enter **Git Commit Message**: `e.g., "Changes in yaml for qa env"`
- Click **Confirm & Proceed**.
- Confirm in the popup to generate a new `revolte.yml` in the repository.

![image](https://github.com/user-attachments/assets/28c641f1-f9f8-4ca3-b5f5-0005d02262ef)


---

### 4. Deploy Application
- Choose:
  - **Environment**: `e.g., QA`
  - **Branch**: `e.g., qatest`
- The updated YAML will be visible in the Configuration section.

![image](https://github.com/user-attachments/assets/0d9a940d-b2cb-42c0-a592-d659e61be802)

---

### 5. Final Deployment
- Click **Confirm & Deploy**.
- If required, add secrets or credentials during the popup by clicking on **Add here** and Click **Confirm** in the confirmation popup.

![image](https://github.com/user-attachments/assets/deef9af5-054a-4f22-a391-eb052993fe47)


- That's it! Deployment will begin and redirects you to the **Runtime Log** for monitoring.

![image](https://github.com/user-attachments/assets/b536afc1-ef4e-4158-adf2-758f3875c5c4)


---

### 6. Post-Deployment
- Deployment should complete.

![image](https://github.com/user-attachments/assets/a78a745b-77cc-4eb8-b39c-30d81bc3f9c4)

Revolte will now provision a existing project with all services and configurations that were defined in the template.

- The page will get redirect to the **Overview** to view **Health Status**, **Application URL**, **Active Instances**

![image](https://github.com/user-attachments/assets/5b7185fe-c5bf-42e0-8f5a-8cab41ecc9a5)


---

> ✅ You’ve now deployed your app using Revolte!
