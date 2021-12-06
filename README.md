# kubernetes-snippet

  ## Start minikube
  
  ` minikube start `
  
  ## Get Cluster Info
  
   ` kubectl cluster-info `
   
  ## View Nodes in the cluster
  
   ` kubectl get nodes `
   
  ## Deploy first app in Kubernetes
  
   ` kubectl create deployment <DEPLOYMENT NAME> --image:<IMAGE LOCATION>`
    
  ## List your deployments
  
   ` kubectl get deployments `
     
  ## Run a  proxy
  
   ` kubectl proxy `
    
  ## List resources
  
   ` kubectl get `
   
  ## Show detailed Info about a resource
  
   ` kubectl describe pods`
    
  ## Print the logs from a container in a pod
  
   ` kubectl logs `
    
  ## Execute a command on a container in a pod
  
   ` kubectl exec `
