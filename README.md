LAB - Temporary Regsitry
========================

This workshop provides a means of deploying a temporary image registry.

If you already have the eduk8s operator installed and configured, to deploy
and view this sample workshop, run:

```
kubectl apply -f https://raw.githubusercontent.com/eduk8s-tests/lab-temporary-registry/master/resources/workshop.yaml
kubectl apply -f https://raw.githubusercontent.com/eduk8s-tests/temporary-registry/master/resources/training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-temporary-registry
```

The training portal is configured to allow anonymous access.
