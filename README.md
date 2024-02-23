# eks-cluster-terraform

Esse é um projeto pessoal feito para a fixação dos conteúdos estudados sobre DevOps. Esse projeto utiliza o terraform para criar um cluster EKS na AWS. E depois é aplicado a configuração do deployment do kubernetes utilizando a imagem do nginx

# Passo a passo #
'''
terraform init
terraform apply --auto-approve
aws eks update-kubeconfig --region us-east-1 --name ascode-cluster
kubectl apply -f deployment.yml
'''


# Tecnologias usadas #
 - Terraform
 - Kubernetes
 - AWS

# Autor

Igor Cândido Rodrigues

https://www.linkedin.com/in/igorc%C3%A2ndido/