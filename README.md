
# Detection engineering for Logscale Detection deployment solution


This helm chart can be used to deploy alerts tied to specific actions using
the Humio/Logscale operator. 

## Requirements

* A Humio/Logscale Cluster managed by the humio-operator
* Existing views
* Existing actions
* A CD solution such as ArgoCD


See values.yaml