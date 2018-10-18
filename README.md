_Context:_
--------
_Some client dev teams will have engineers who are not experienced in cloud technologies. To prevent accidental loss of systems, those users should not have permissions to delete systems._



Scope
--------
This card addresses the IAM functionality. Create a custom role with allows users to create and modify VMs/compute resources, but cannot delete them. Create a user with those permissions to demonstrate this capacity.

The solution should include the following GCP services:

- IAM

Notes
-----

This is a free form project. The actual process won't necessarily take too much time. You can complete this via the console, and if you want to try using the `gcloud` tool, go for it.

The purpose of this project is to get familiar working with GCP's IAM implementation. IAM is a cornerstone to all CSPs, and they all implement it differently. Understanding *how* GCP does it will be critical to succeeding on the Cloud Architect exam.
