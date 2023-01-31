# This is the README file for the project

# This is a Kubernetes Task.
# The task statement is stated below:

Assignment:
  Project Agenda: To deploy the application using the Kubernetes
  dashboard

Description:
    Your organisation is looking to create a multi-tier application based on
    PHP and MySQL. Your job is to deploy this application using the
    Kubernetes dashboard. Create a user (service account) with the name of
    Sandry and make sure to assign her an admin role. WordPress and
    MySQL Pods should use node3 as an NFS storage server using static
    volumes. WordPress applications must verify the MySQL Service before
    getting it deployed. If the MySQL Service is not present, then the  
    WordPress Pod should not be deployed. These all should be restricted
    to the namespace called cep-project1 and must have 3 svcs, and 3 Pods
    as a max quota. All sensitive data should be used using secrets and
    non-sensitive data using configmaps.

Tools Required: kubeadm, kubectl, kubelet, and Docker

Expected Deliverables:
  Note: Kubernetes cluster needs to be set up in your lab machine to
  perform the above project

# All the manifest files required for this project are present in the repository, along with the screenshots and a PDF file for steps to perform
