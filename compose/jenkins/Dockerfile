FROM jenkins/jenkins:lts

# Install Terraform
USER root
RUN apt-get update && \
    apt-get install -y wget unzip && \
    wget https://releases.hashicorp.com/terraform/1.5.0/terraform_1.5.0_linux_amd64.zip && \
    unzip terraform_1.5.0_linux_amd64.zip && \
    mv terraform /usr/local/bin/ && \
    rm terraform_1.5.0_linux_amd64.zip