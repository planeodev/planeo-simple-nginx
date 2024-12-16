# planeo-simple-nginx
This is a simple helm chart that runs nginx on port `:80`

## requirements
- a working `kubernetes` cluster
- a configured `kubectl` CLI
- a `helm` client installed on your machine

## usage
`helm install simple-nginx ./charts/simple-nginx --namespace simple-nginx --create-namespace`

## license
See [LICENSE](https://github.com/planeodev/planeo-simple-nginx/blob/master/LICENSE) for full details
