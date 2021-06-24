1. Mark 3 nodes with ELASTIC LABELS to make sure elastic will only be schedulled on those instances.
~~~
kubectl lables [NODES] elastic=schedulled
~~~
2. Deploy master instances (make sure longhorn is deployed and storage class is configured as default)
