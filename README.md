# Sample Armory Agent remote account in Spinnaker mode

A simple Helm sample of Armory agent in Spinnaker mode with remote account

# Usage

```
helm template remote-agent remote-agent

helm install remote-agent remote-agent -n <your namespace>

helm uninstall remote-agent remote-agent -n <your namespace>
```

# Reference Link

- Install the Armory Agent Service Using a Helm Chart (https://docs.armory.io/scale-agent/install/install-agent-service-helm/)

- Secrets with S3 (https://docs.armory.io/continuous-deployment/armory-admin/secrets/secrets-s3/)
