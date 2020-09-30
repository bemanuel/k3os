# k3os on Digital Ocean 

## Quick Start

* Tested on Packer v1.6

1. Build Digital Ocean snapshot using [Packer](https://www.packer.io/): 

```
packer build -var-file=vars.json template.json
```

## Vars

| Var | Description |
| --- | ----------- |
| do_token | [Token](https://cloud.digitalocean.com/account/api/tokens) |
| iso_url | K3Os [Release](https://github.com/rancher/k3os/releases) |
| region | DO Region |

## Notes

Can define IP and other parameter on config/cloud.yml, according to [Configuration Reference](https://github.com/rancher/k3os/blob/master/README.md#configuration-reference)
