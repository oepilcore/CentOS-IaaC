# CentOS-IaaC

This is just a simple vagrant file script for you to deploy automatically HTTPD Service and upload your HTML or any simple script to your Vagrant-vms

## Installation

Use git clone.
```bash
git clone https://github.com/oepilcore/CentOS-IaaC.git
```
Copy the file to your vagrant-vms folder
*For example mine folder was installed on drive D
```bash
mv CentOS-IaaC /d/vagrant-vms/
```

## Usage

```bash
cd /vagrant-vms/CentOS-IaaC
vagrant up
```

## Note

Please take note of some lines, please change these line using your private IP
```bash
config.vm.network "private_network", ip: "192.168.69.25"
```

You can change the resource for your website on these lines. in this line, I've used tooplate to download the HTML Scripts
```bash
wget https://www.tooplate.com/zip-templates/2109_the_card.zip
```
## Source
Free HTML Source: https://www.tooplate.com/free-templates
