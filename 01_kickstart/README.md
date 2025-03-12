##### Chart.yaml contains the metadata for the chart
##### values.yaml contains the different values for deployments, services and more.
##### templates directory has all the manifest files for the application

--- 

Make sure to stay in the directory where Chart.yaml exist and then for packaging the chart, run the following command
```
helm package .
```

