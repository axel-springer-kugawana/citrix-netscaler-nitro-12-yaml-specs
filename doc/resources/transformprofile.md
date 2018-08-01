# Resource transformprofile

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : name

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/transformprofile?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| name | No | string |
| type | No | URL |
| onlytransformabsurlinbody | No | ON, OFF |
| comment | No | string |
