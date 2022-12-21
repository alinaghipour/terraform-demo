
# requirments
## install terreform

wget https://releases.hashicorp.com/terraform/1.3.6/terraform_1.3.6_linux_amd64.zip

sudo apt-get update
sudo apt install zip unzip

echo $PATH

sudo unzip terraform_1.3.6_linux_amd64.zip -d /usr/local/bin


--------
## config ssh-keygen

ssh-keygen -t rsa -b 4096 -C "sample@gmail.com"
