# Deploy in OpenShift

fabdulkh$ oc create -f crossplat-app-linux.yaml 

deployment.apps/crossplat-app-linux created

service/crossplat-app-linux created

route.route.openshift.io/crossplat-app-linux created

fabdulkh$ oc create -f crossplat-app-windows.yaml 

deployment.apps/crossplat-app-windows created

service/crossplat-app-windows created

route.route.openshift.io/crossplat-app-windows created
