# custom-errorpage-with-helm

- Create a configmaps for the errorpages ![404Errorpage](404errorconfig.yaml)
- Run `helm create nginx-custom-errors` this create the helmchart
- Update helm template with the script im [Configmap](configmap.yml)
- update values.yaml 
- Deploy the helmchart
