# An ever evolving test / learn project, using the Hashistack tools (Terraform, Consul, Vault, Packer, etc)

I will be using [HashiCups](https://github.com/hashicorp-demoapp) (a demo coffee shop application made up of several microservices) to muck around in a DevOps(ish) way

-=-=-

Will try this on GCP, so you need to provide the credentials and the project number:

```
export GOOGLE_PROJECT="123123123123"
export GOOGLE_CREDENTIALS="credentials.json"
```

Task: Spin up a VM that will be used for Consul server

