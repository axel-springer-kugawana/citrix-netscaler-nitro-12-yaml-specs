# Resource dnsprofile

Spec for **dnsprofile** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/domain-name-service/dnsprofile/dnsprofile/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : dnsprofilename

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/dnsprofile?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| dnsprofilename | No | string |
| cacheecsresponses | No | ENABLED, DISABLED |
| cachenegativeresponses | No | ENABLED, DISABLED |
| cacherecords | No | ENABLED, DISABLED |
| dnsanswerseclogging | No | ENABLED, DISABLED |
| dnserrorlogging | No | ENABLED, DISABLED |
| dnsextendedlogging | No | ENABLED, DISABLED |
| dnsquerylogging | No | ENABLED, DISABLED |
| dropmultiqueryrequest | No | ENABLED, DISABLED |

