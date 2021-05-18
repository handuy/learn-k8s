Get the YAML for a new namespace called 'myns' without creating it

kubectl create ns myns --dry-run=client -o yaml
