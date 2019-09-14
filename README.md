# Interactive EC2 instance creation via aws cli

# Requirements
  - awscli installed,e.g.:
```
pip3 --user install awscli
```
  - configured aws profile, e.g.:
```
aws configure
```
  - imported public key (rsa 4096+ bits), e.g.:
```
aws ec2 import-key-pair --key-name "$USER"_$(date +"%F_%H-%M-%S") --public-key-material file://~/.ssh/id_rsa.pub
```
