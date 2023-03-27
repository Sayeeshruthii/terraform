# 1. Create service principle in Azure
# az ad sp create-for-rbac --name SayeeAKSRole --role Contributor --scopes /subscriptions/f693f291-3bd0-4038-861c-56769a6e0a28
 <!-- { -->
  <!-- "appId": "eca753f0-59f4-4f30-b3c7-eebdc03eb1da",
  "displayName": "SayeeAKSRole",
  "password": "wLu8Q~xacOML3x2pAOInyGaFNwTZ4w._PqBvWb4d",
  "tenant": "96048087-a382-4fc0-a029-273ce64d679b"
} -->

# 2.Specify credentials in Terraform block and env var
<!-- export ARM_SUBSCRIPTION_ID="f693f291-3bd0-4038-861c-56769a6e0a28"
export ARM_TENANT_ID="96048087-a382-4fc0-a029-273ce64d679b"
export ARM_CLIENT_ID="eca753f0-59f4-4f30-b3c7-eebdc03eb1da"
export ARM_CLIENT_SECRET="wLu8Q~xacOML3x2pAOInyGaFNwTZ4w._PqBvWb4d" -->

# 3.Connect to aks with CLI
<!-- az account set --subscription f693f291-3bd0-4038-861c-56769a6e0a28
az aks get-credentials --resource-group sayeers --name aks -->

# 4.kubectl on windows 
<!-- https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/ -->

# 5. Create backend and microservice and Dockerfile push to github
<!-- https://nodejs.org/en/docs/guides/nodejs-docker-webapp
https://www.freecodecamp.org/news/how-to-create-a-react-app-with-a-node-backend-the-complete-guide/ 
https://blog.back4app.com/microservices-nodejs/#Step_2_Lets_Begin-->

# 6. Create Azure Devops Pipeline and Release
<!-- https://www.coachdevops.com/2021/09/how-to-deploy-docker-containers-into.html -->