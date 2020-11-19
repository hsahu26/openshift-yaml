# openshift-yaml
OpenShift YAML examples


## Deploy Application from Dockerfile

blog-django-py-app:
- https://learn.openshift.com/introduction/deploying-python/
- https://github.com/openshift-katacoda/blog-django-py

```bash
# Check resources
oc get all -o name

# Export resources to YAML
oc get <resource> -o yaml > <resource_type>.yaml

# Create resources from YAML
oc apply -f ./blog-django-py-app
```