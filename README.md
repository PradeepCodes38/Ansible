# How to Install Ansible
    Installing Ansible on Ubuntu is straightforward. Here are the steps to install Ansible on an Ubuntu system:
# Step 1: Update Your System
    sudo apt update
    sudo apt upgrade -y
# Step 2: Install Ansible
    You can install Ansible directly from the official Ubuntu repositories, but it’s often better to install it using the Ansible PPA to ensure you get the latest version.
# Add the Ansible PPA:
    sudo apt update
    sudo apt install software-properties-common -y
    sudo add-apt-repository --yes --update ppa:ansible/ansible
# Install Ansible:
    sudo apt update
    sudo apt install ansible -y
# Step 3: Verify the Installation
     ansible --version
