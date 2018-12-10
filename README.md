# rancher-cli-examples

## CLI

https://github.com/rancher/cli/releases

## Check Version

rancher --version

## Login

https://rancher.com/docs/rancher/v2.x/en/user-settings/api-keys/

rancher login https://<URL> --token <your token>

## Basics

rancher context switch

rancher ps

rancher namespaces

rancher clusters

rancher nodes

## Kubectl

rancher kubectl get nodes

## Catalog

rancher catalog --help

rancher catalog ls

rancher catalog add --help

rancher catalog add theo-repo https://github.com/FuriKuri/charts

rancher catalog ls

## App

rancher app --help

rancher app ls

rancher app install --help

rancher app install --set service.type=LoadBalancer --set helloWorld="Hello CLI" --set ingress.enabled=false --version 0.0.1 jenkins hello-jenkins

rancher ps