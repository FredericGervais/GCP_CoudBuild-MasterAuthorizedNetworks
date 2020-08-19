# GCP_CoudBuild-MasterAuthorizedNetworks

This proof of concept allows you to use Cloud Build and interact with a GKE cluster that is using the Master Authorized Networks feature

Usage:
```
gcloud builds submit --substitutions=_CLOUDSDK_COMPUTE_ZONE="REPLACE_ME_ZONE",_CLOUDSDK_CONTAINER_CLUSTER="REPLACE_ME_CLUSTER_NAME"
```
