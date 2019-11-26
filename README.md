# Sagemaker Bring Your Own Model Python

The code here will be used to showcase the Bring Your Own Model capabilities of Amazon Sagemaker.

## Instance Setup

In this Step, we will configure the Sagemaker Instance that we are going to use throughout this session.

### Lifecycle Management

In this section we will configure the Lifecycle Policy for our Sagemaker instance

1. Go to create a new Lify 

```
#!/bin/bash

set -e
pip install --upgrade pip
git config --system user.name "<YOUR NAME>"
git config --system user.email "<YOUR@EMAIL>"
```

### Add Repository

1. URL `https://github.com/purnesh/sagemaker-byom-python`
2. Branch Name `master`
3. Create **New Secret**
4. Add Repository

### Role Creation

1. Create a new Role
2. Attach `EC2ContainerRegistryFullAccess` policy to the newly created role. 

### Verification and Debugging

1. Go to Cloudwatch
2. Click on **Log Groups** in the left hand menu
3. Go to `/aws/sagemaker/NotebookInstances`
4. Click on the appropriate option to view logs

