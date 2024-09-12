# Vaultwarden

Get Admin Token
```bash
kubectl get -n vaultwarden secrets/vaultwarden --template='{{index .data "admin-token"}}'|base64 -d
```
