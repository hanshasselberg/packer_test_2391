# Repo to reproduce https://github.com/mitchellh/packer/issues/2391

```
PACKER_NO_COLOR=1 packer build problem.json > problem.log
PACKER_NO_COLOR=1 packer build no_problem.json > no_problem.log
```
