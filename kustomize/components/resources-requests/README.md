# Update the resources requests of the Online Boutique apps

The Online Boutique apps are lightweight but the requests could limit your ability to deploy correctly on small tests clusters. You may need to change the requests to target and this Kustomize variation will help you setting this up.

## Change the default requests via Kustomize

To change the requests for all Deployments, you can leverage this Kustomize variation. By default, it sets requests at 50m CPU and 32Mi of memory. Edit the kustomization YAML to use your own values.

Limits are not modified. Ensure your cluster can run smoothly.
