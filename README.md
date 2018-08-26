# my-k8s-cheat-sheet

## Cluster managing 
### get resource description

``` kubectl get <resource> <resource-name> ```

``` kubectl describe <resource> <resource-name> ```

*yaml*
``` kubectl get <resource> <resource-name> -o yaml```

### label a resource
``` kubectl label <resource> <resource-name> <label-key>=<label-value> ```

### remove a label from a resource
``` kubectl label <resource> <resource-name> <label-key>-```

### adding a role to a node 
``` kubectl label nodes <node-name> node-role.kubernetes.io/<role-name>="" ```

### remove a role from a node 
``` kubectl label nodes <node-name> node-role.kubernetes.io/<role-name>-```
