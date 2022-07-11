# bud-product-assess

WIP - [TODO](TODO)
Contains a list of services that creates the assess product

This repo is entirely owned by the Product team responsible for the AuthNZ product and is referenced by the bud-product-registry.

Inspired by [ArgoCD Applicationsets](https://argo-cd.readthedocs.io/en/stable/user-guide/application-set/)

## To add a service to a product:

* Copy template/example-service directory to /services
* Change the name of the /services/example-service to the name of the service
* modify the contents of the directory
    - definition: This defines details of the service
    - default: **SANE** defaults that will applied to all clusters/environments
    - custom: contains files named after clusters with custom settings
* Add service name with to [Services.md](Services.md)

:warning: **DO NOT** under any circumstances modify the deploy directory without discussing without considering the impact it will have on other services/products!! :warning:
