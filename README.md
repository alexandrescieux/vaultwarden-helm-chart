# Vaultwarden

## Template

````bash
helm template vaultwarden --namespace vaultwarden .
````

## Installati2on

````bash
helm install vaultwarden --create-namespace --namespace vaultwarden .
````

## Mise à jour

````bash
helm upgrade vaultwarden --install --namespace vaultwarden .
````

## Suppression

````bash
helm delete vaultwarden --namespace vaultwarden 
````