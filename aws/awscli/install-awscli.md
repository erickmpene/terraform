### Install awscli on centos7
#### 1. Install unzip
```sh
yum update && yum install unzip -y
```
#### 2. Unzip
```sh
unzip awscliv2.zip
```
#### 3. Install awscli
```sh
sudo ./aws/install
```
#### 4. Export Path
```sh
export PATH=$PATH:/usr/local/bin
```

#### 5. Configure awscli with your credentials 
```sh
aws configure
```
AWS Access Key ID [None]: => # Your Access Key (access programmation)

AWS Secret Access Key [None]: => # Your Secret Key

Default region name [None]: => # Default region. Example : us-east-1 

Default output format [None]: => json (for me)

#### Enjoy ! d(o_o)b 