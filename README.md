# helm-repo-for-bitnami-postgresql-ha-onlyservice
```
helm upgrade --install postgresql bitnami/postgresql-ha/ -f bitnami/postgresql-ha/values.yaml --create-namespace --namespace postgresql --set postgresql.replicaCount=3 --set persistence.enabled=false --set persistence.enabled=false --set service.type=ClusterIP --set postgresql.username=postgres --set postgresql.password=Dexter123 --set postgresql.database=dexter --kube-context=arn:aws:eks:us-east-2:02XXXXXXXXX6:cluster/eks-demo-cluster-dev
```
