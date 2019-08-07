# kubeyes
Data driven reliability of Kubernetes

Kubeyes can quantize all kinds of reliability indicator of Kubernetes and drive the improvement. 

It bases on the List&Watch mechanism of Kubernetes to reflects latest status of resources and recorsd them to Elastic as history for trend analysis. 

## Key Function
- Visual account book of k8s object 
- Event based analysis for control plane health and performance
- Bin packing and utilization dashboard

## EBA 
use event + FSM (eFSM) to analysis creation and termination of Kubernetes resource. 
