# Tips for Kubernetes Jobs deployment strategies in Continuous Delivery scenarios

Examples about how to deal with immutable Job updates.

You can try it by running:

kubectl apply -f https://raw.githubusercontent.com/SUSE-Technical-Marketing/fleet-job-deployment-examples/rmahique-patch-1/git-repo-job-with-random-name.yaml

or 

kubectl apply -f https://raw.githubusercontent.com/SUSE-Technical-Marketing/fleet-job-deployment-examples/rmahique-patch-1/git-repo-jobs-with-ttlsecondsafterfinished.yaml


Note: these are setup to be used on a single cluster. If you want to deploy to multiple cluster please change the namespace from "fleet-locatl" to "fleet-default".
