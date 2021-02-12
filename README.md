# openshift-yolo

OpenShift CronJob to check if updates are available, and if so, upgrade the
cluster to the latest version.

By default it is scheduled every hour at 53 minutes, but you can break your
cluster whenever you want :)

```bash
oc apply -f yolo.yaml
```