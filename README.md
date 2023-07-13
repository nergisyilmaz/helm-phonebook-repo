```bash
helm repo add helm-phonebook-repo https://raw.githubusercontent.com/nergisyilmaz/helm-phonebook-repo/main
helm install phonebook-app helm-phonebook-repo/phonebook-chart
```

- To use own images execute as below:

```bash
helm install phonebook-app helm-phonebook-repo/phonebook-chart --set webserver_image=<image-name> --set resultserver_image=<image-name>
```