# AWS IAM Cloud Security Project
## 🎯 EC2 Access Control with IAM Policies

This project demonstrates how to securely control access to EC2 instances using IAM policies, groups, and users. The objective is to enforce fine-grained permissions so that IAM users can only start, stop, and describe EC2 instances tagged a certain way (e.g., Env=development), while being denied access to other instances.

## 🔐 Objective

Restrict EC2 access based on resource tags.

Allow users to start, stop, and describe only specific EC2 instances.

Prevent users from creating/modifying tags or accessing non-assigned resources.

Use IAM groups and policies to simplify access management.

## 🧱 Components Created
**EC2 Instances**:	Multiple instances with unique Environment tags like Development, Staging, Production.

**IAM Policies**: Custom policies allowing EC2 access only to instances tagged Environment=Development.

**IAM Groups**: A group (Dev-EC2-Access) associated with the custom policy.

**IAM Users**: IAM users added to the group for scoped access control.

## 🛠 Tools Used
AWS IAM

Amazon EC2

AWS Console

JSON IAM Policies

## 🙏 Acknowledgments
This project was inspired by a hands-on lab provided by NextWork.

Credit to NextWork for the guidance and structure used in building the IAM policies and EC2 access configurations.
