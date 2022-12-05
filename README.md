
be sure to change the label:
<hub> $ oc edit managedcluster local-cluster
...
labels:
...
    cloud: Amazon
    cluster.open-cluster-management.io/clusterset: all-clusters
...

--> The local cluster should be moved into the ManagedClusterSet "all-clusters"
