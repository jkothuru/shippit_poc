node {
    stage('Code Checkout') { 
    	checkout scm
    }

    stage('Terraform') {
    	terraform init
    	terraform plan
    	terraform apply --autoapprove
    	}
    }
