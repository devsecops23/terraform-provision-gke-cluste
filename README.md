# Learn Terraform - Provision a GKE Cluster

This repo is a companion repo to the [Provision a GKE Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/gke), containing Terraform configuration files to provision an GKE cluster on GCP.

This sample repo also creates a VPC and subnet for the GKE cluster. This is not
required but highly recommended to keep your GKE cluster isolated.

Version.tf has provider info
***Steps***
Update terraform.tfvars:
**    **project_id =#  "your project id"
    **region**     = "your default region"

Next run gcloud auth login. This will take you to web brower where you can login to your gcloud account

Next go to your github folder where .tf files are and run github init and then github apply
Version.tf has provider info
