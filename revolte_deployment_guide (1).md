# Revolte Application Deployment Guide

Follow the steps below to deploy your application using the Revolte platform.

---

### 1. Access the Dashboard
- Open the Revolte **'Projects'** dashboard.
- Click on the **'Deploy App'** button.

---

### 2. Provide Project Details
- Enter the following:
  - **Project Name**: `your-project-name`
  - **Application Name**: `your-application-name`
  - **Repository**: `your-git-repo-url`

---

### 3. YAML Configuration
- A **YAML Configuration** page will be displayed with preset selection and YAML editor.
- **Select Environment**: `preview` / `qa` / `staging` / `prod`
- **Select Branch**: `main` / `develop` / `feature/*` 
- Click on **'Choose Services'** and select the preset as **'Webapp'**.

---

### 4. Edit and Commit YAML
- The default YAML will be populated in the editor.
- Make any necessary changes (e.g., environment variables, replicas, ports).
- Enter **Git Commit Message**: `e.g., "Updated deployment config for webapp"`
- Click **Confirm & Proceed**.
- Confirm in the popup to generate a new `revolte.yml` in the repository.

---

### 5. Deploy Application
- The **Deploy Application** page will display how/where the code will be deployed.
- Choose:
  - **Environment**: `e.g., preview`
  - **Branch**: `e.g., dev`
- Ensure the updated YAML is visible in the Configuration section.

---

### 6. Final Deployment
- Click **Confirm & Deploy**.
- If required, add secrets or credentials during the popup.
- Click **Confirm** in the confirmation popup.
- Deployment will begin.
- The page should redirect to the **Runtime Log** for monitoring.

---

### 7. Post-Deployment
- Deployment should complete.
- The page should redirect to the **Overview** to view **Health Status**, **Application URL**, **Active Instances**

---


> ✅ You’ve now deployed your app using Revolte!
