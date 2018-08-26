# my-k8s-cheat-sheet

## Cluster managing 

### label a ressource
``` kubectl label <resource> <resource-name> <label-key>=<label-value> ```

### remove a label from a ressource
``` kubectl label <resource> <resource-name> <label-key>-```

### adding a role to a node 
``` kubectl label nodes <node-name> node-role.kubernetes.io/<role-name>="" ```

### remove a role from a node 
``` kubectl label nodes <node-name> node-role.kubernetes.io/<role-name>-```
