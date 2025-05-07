---
layout: archive
title: ""
permalink: /reu/aws_setup
author_profile: false
---

# AWS SageMaker Setup Guide

This guide walks you through setting up a SageMaker notebook instance using credentials and configurations from a shared CSV file.

## Prerequisites
- **CSV file** containing:
  - AWS login URL (e.g., `https://your-account.signin.aws.amazon.com/console`)
  - User ID and password
  - (Optional) Default region or other configurations

---

## Step 1: Log in to AWS
1. Open the shared CSV file and locate:
   - **AWS Login URL** (e.g., `https://[account-id].signin.aws.amazon.com/console`)
   - **User ID** and **Password**  
2. Navigate to the URL in your browser and log in with the credentials.

---

## Step 2: Open SageMaker
1. After logging in, search for **"SageMaker"** in the AWS Services search bar.
2. Click **Amazon SageMaker** to open the dashboard.

---

## Step 3: Create a Notebook Instance
1. In the left sidebar, go to **Notebook** > **Notebook instances**.
2. Click **Create notebook instance** and configure:
   - **Name**: your preferred name.
   - **Instance type**: `ml.t3.medium` (or `ml.g4dn.xlarge` for GPU support).
   - **Volume size**: Set to **10GB** (required for larger datasets).
3. Under **Git repositories**, click **Add a repo**:
   - **Repository source**: GitHub.
   - **URL**: `https://github.com/symplecticgeometry/equivariant-neural-networks-and-equivarification.git`.
   - Check **Clone recursively** (if the repo has submodules).

---

## Step 4: Launch JupyterLab
- Wait for the instance status to change to **"InService"** (2–5 minutes).
- Click **Open JupyterLab**.

---

## Step 5: Verify Python Environment
1. Create a new Jupyter Notebook (**Python 3** kernel).
2. Run the following to check the active environment:
   ```python
   import sys
   print(sys.executable)  # The path before `/bin/python` is the env name.
