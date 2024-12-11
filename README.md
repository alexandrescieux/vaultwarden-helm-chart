# Vaultwarden

## Template

````bash
helm template vaultwarden --namespace vaultwarden .
````

## Install

````bash
helm install vaultwarden --create-namespace --namespace vaultwarden .
````

## Update

````bash
helm upgrade vaultwarden --install --namespace vaultwarden .
````

## Delete

````bash
helm delete vaultwarden --namespace vaultwarden 
````