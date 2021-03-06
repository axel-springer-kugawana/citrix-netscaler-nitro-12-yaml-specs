# Resource cmppolicy

Spec for **cmppolicy** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/compression/cmppolicy/cmppolicy/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/cmppolicy?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| resaction | No | cmpaction.name |
| rule | No | string |

