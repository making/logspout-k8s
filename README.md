## Logspout on Kubernetes

```
cp logspout-secret.yml.example logspout-secret.yml
```

Change `route-uri`.

You can encode the uri as follows:

```
echo syslog+tcp://example.com:514 | base64
```