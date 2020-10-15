# ami

# Installation

# Download packer instruction for ubuntu

```
$ curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
```

# VALIDATE INSTRUCTION

```
packer validate ubuntu-ami.json
```

# PACKER BUILD INSTRUCTIONS 
pass aws_acess_key, aws_secret_key, aws_region , aws_subnet, aws_prod_id as a variable using following command.
```
packer build ubuntu-ami.json
```

