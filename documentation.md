# Accessing ArgoCD and Gitea Consoles

This document provides instructions on how to access the ArgoCD and Gitea consoles in the microk8s environment.

## ArgoCD

The ArgoCD server is exposed via a NodePort service.

*   **URL**: `http://xubuntu:32210` or `https://xubuntu:31353`
*   **Username**: `admin`
*   **Password**: `Lachlan080!`

## Gitea

The Gitea server is also exposed via a NodePort service.

*   **URL**: `http://xubuntu:30842`
*   **SSH**: `ssh://<username>@xubuntu:30222`

**Note**: You will need to create a user in the Gitea web interface before you can use the SSH service.
