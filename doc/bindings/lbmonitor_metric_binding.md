# Binding lbmonitor_metric_binding

Spec for **lbmonitor_metric_binding** binding - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/load-balancing/lbmonitor_metric_binding/lbmonitor_metric_binding/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

- monitorname
- metric

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding/<name>` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/lbmonitor_metric_binding` |

## Fields

| Name | Type |
|----|----|
| metric | string |
| metricthreshold | double |
| metricweight | double |
| monitorname | lbmonitor.monitorname |

