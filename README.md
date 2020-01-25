# Artifactory on AWS EC2

This sample repository shows the automated provisioning of JFrog's __Artifactory__ on AWS EC2 instances using Terraform.


### Setup

```bash
terraform init
```

### Provision

```bash
terraform apply --auto-approve
```

### Access Artifactory

Once provisioned, navigate to the external IP address of the provisioned EC2 instance to access Artifactory by using this link:

```
http://[AWS_EC2_INSTANCE_EXTERNAL_IP]:8081
```

The default username and password is admin/password as explained in the Artifactory's documentation wiki.