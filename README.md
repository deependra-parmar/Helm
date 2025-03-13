### For packaging the chart, run
```
helm package .
```

---

### For creating a chart, run
```
helm create helloworld
```

--- 

### For creating a release, run
```
helm install helloworld .
```

--- 

### For listing all releases, run
```
helm list -a
```

---

### For uninstalling the helm chart, run
```
helm uninstall myhelloworld
```

---

### In order to get the generated valid manifests from helm, run
```
helm install --generate-name --dry-run --debug .
```