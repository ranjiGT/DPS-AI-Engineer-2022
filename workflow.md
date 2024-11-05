| Workflow     | Description       |
|--------------|----------------|
| managed-identity-app-repo | Create and configure a Managed Identity for an application repository. It performs various steps to set up Azure resources, assign necessary permissions, and configure GitHub secrets for seamless integration between the AKS cluster and GitHub Actions. |
| additional role assignment| Designed to assign a specific role to an Azure user or service principal on a specified scope (such as a resource group, subscription, or individual resource). It enables users to dynamically assign Azure Role-Based Access Control (RBAC) permissions by specifying inputs during the manual trigger of the workflow. |
| assign-la-join-role | Assigns the AKS Log Analytics Join role to a Managed Identity in response to a labeled GitHub issue. This process automates the setup required for specific role assignments in Azure when an issue with a particular label is detected. |
| cluster-creation | Order clusters via CaaS pipeline |
| cluster-deprovision | After cluster creation to decommission the created cluster with its roles |
| cluster-import | To import a cluster  |
| cluster-validation | Validation checks on cluster  |
| federated-credentials-deletion | To delete federated credentials associated with a Managed Identity (MI) for an Azure Kubernetes Service (AKS) cluster. It can be triggered manually and requires specific inputs related to the Azure subscription and the AKS cluster name.|
| gke-cluster-creation | To automate the process of creating a Google Kubernetes Engine (GKE) cluster based on specific issues labeled in a GitHub repository. The workflow is triggered by events related to issues, particularly when they are labeled, opened, or edited. |
| remove additional role |  To automate the process of removing a specified Azure role assignment from a user or service principal within a specific subscription and scope.|
| managed-identity-creation |  To create managed identity |
| renovate | To automate the process of updating dependencies and managing versions for a software tool.  |
