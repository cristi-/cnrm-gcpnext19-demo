# Add the gcp-gcs-writer-sa-key secret

Download the ServiceAccount JSON and use it to create a Secret. E.g.:

```bash
kubectl create secret generic gcp-gcs-writer-sa-key --from-file=key-content=/home/gdonovan/Downloads/cnrm-gcpnext19-demo-e65312b33d53.json
```