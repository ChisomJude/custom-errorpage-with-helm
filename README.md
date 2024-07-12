# custom-errorpage-with-helm

- Create a configmaps for the errorpages [404Errorpage](404errorconfig.yml) and [404Errorpage](500errorconfig.yml)
- Run `helm create nginx-custom-errors` this create the helmchart
- Update helm template with the script in [Configmap](configmap.yml) (nginx-custom-errors/templates/configmap.yaml)
- update values.yml  ( located in your nginx-custom-errors folder)
- Deploy the helmchart `helm install nginx-custom-errors ./nginx-custom-errors`
