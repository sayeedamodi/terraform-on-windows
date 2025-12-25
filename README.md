
# Download and Install Terraform on Windows (Manual Method)

This guide explains how to manually download, install, and configure **Terraform** on a Windows system.

---

## Prerequisites

- Windows 10 or later  
- Administrator access  
- Internet connection  

---

## Step 1: Download Terraform

1. Open the official Terraform download page:  
   [Terraform Downloads - Windows](https://developer.hashicorp.com/terraform/install#windows)
2. Download the **Windows (AMD64)** ZIP file.

---

## Step 2: Extract the ZIP File

1. Locate the downloaded ZIP file.
2. Extract it to any temporary location.
3. Inside the extracted folder, you will find the **Terraform binary (`terraform.exe`)**.

![Extract Terraform](https://github.com/user-attachments/assets/d8c12b5e-b69d-442d-9b68-a225a0519ea5)

---

## Step 3: Create a Terraform Directory

1. Navigate to `C:\Program Files`
2. Create a new folder named:

```

terraform

```

3. Copy `terraform.exe` into this newly created folder.

4. Now copy the folder path.

![Terraform Folder](https://github.com/user-attachments/assets/274d7bc5-b7ce-40f0-9873-98b11f2d952e)

---

## Step 4: Add Terraform to System PATH

```

C:\Program Files\terraform

````

2. Open **Settings** → search for **Environment Variables**
3. Select **Edit the system environment variables**
4. Click **Environment Variables**
5. Under **System variables**, select **Path** → click **Edit**
6. Click **New** and paste the copied Terraform path
7. Click **OK** on all open windows

![Edit Path](https://github.com/user-attachments/assets/f0481be4-cd42-440e-ab28-40f0bee489d8)

---

## Step 5: Verify Installation

1. Open **Command Prompt** or **PowerShell**
2. Run one of the following commands:

```bash
terraform
````

or

```bash
terraform version
```

If Terraform is installed correctly, you will see the version information displayed.

![Terraform Version](https://github.com/user-attachments/assets/b84d0ff8-32ef-476b-b73a-8156ac5cd5c7)

---

## Installation Complete

**Boom!** You have successfully downloaded and installed Terraform on Windows manually.

You can now start using Terraform to manage your infrastructure.

---

## Optional: First Terraform Commands

Once installed, you can try the following Terraform commands:

```bash
terraform init     # Initialize a Terraform working directory
terraform plan     # Show the execution plan
terraform apply    # Apply changes to reach desired state
```

These commands will help you get started with Terraform quickly.


## Author @Sayeedamodi
```




