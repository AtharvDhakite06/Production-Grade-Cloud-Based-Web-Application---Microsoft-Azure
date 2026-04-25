# Day 01 — Azure Account Setup & Resource Group Configuration

## Azure Resource Group

What:
A logical container that holds related Azure resources. Think of it as a folder for your cloud resources.

Why:
Keeps all project resources together
Allows bulk deletion (delete the group → deletes everything inside)
Enables unified cost monitoring
Simplifies role-based access control (RBAC)

Where used:
Created as rg-cloud-project in East US (or your chosen region). Every resource created in this project is deployed inside this resource group.
