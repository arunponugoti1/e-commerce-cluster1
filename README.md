# e-commerce-cluster1
# kubectl api-resources: It will shows the cluster level namespace level resources and find the api version
# I'll deploy simple nginx web app
# Added service also
# Today i have created New GKE cluster through UI
# I can write the code in local vscode and push it to the github and from there I can pull code to the GKE cluster
# This is what excatly I want, so i have achieved today something,Thanks for the day
# I have created new one 
# Labels: Uses for two reasons 1. identify 2.which we use for some functionlity for selectors
# Annotations: We use this for external resources in k8s
# database usernamegive in the configmaps 
# Database passwords give me in the secrets
====================
Sets:
ReplicaSets: It will create the desired state of the Pods, by using this resource we can create pods but not update
Deployments: This is the Ideal for the stateless or static pods to deploy in the K8s. When you update pods with latest image it will auotmatically deploy latest one.
    When you upgraded new version it will use the replicasets and first delete one pod and create new version again delete old version and create new version so you no need downtime for this.
    


