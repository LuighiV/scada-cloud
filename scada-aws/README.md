# Deploying in AWS.

To deploy in AWS is required to have installed the client of AWS.

In case of archlinux the installation process is:

```
yay -S aws-cli
```

When the cli tool is installed you could perform:
```
aws --version
```
This is for the cli version 1, you can also install the version 2 with:

```
yay -S aws-cli-v2-bin
```

To save the private_key, perform:
```
terraform output private_key > id_rsa

chmod u+x id_rsa
chmod 600 id_rsa
```
