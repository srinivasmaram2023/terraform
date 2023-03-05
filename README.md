# Pre-Requisites
Step 1: Create public and private key using the below command
$ssh-keygen

# Execution Flow
Step 1: Clone the terraform repo

$git clone https://github.com/akhilvaka2/Terraform.git && cd Terraform

Step 2: add public key in keypair resource

$vi infra.tf

Step 3: Initialize terraform to install aws provider plugin

$terraform init 

Step 4: Apply
