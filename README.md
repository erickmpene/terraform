### Install Terraform CLI on CentOS 7

#### 1. Run command :
```sh
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
sudo yum update
sudo yum -y install terraform
```
#### 2. Add path to your in your .bashrc's file
```sh
nano ~/.bashrc
```
Add => _export PATH=$PATH:/bin_

```sh
source ~/.bashrc
terraform --version
```
=> Terraform v1.5.6
on linux_amd64

#### 3. Enable commpletion
```sh
terraform -install-autocomplete
```

### Enjoy ! d(o_o)b

