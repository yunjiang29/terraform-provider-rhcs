---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rhcs_hcp_default_ingress Resource - terraform-provider-rhcs"
subcategory: ""
description: |-
  Edit a cluster ingress (load balancer)
---

# rhcs_hcp_default_ingress (Resource)

Edit a cluster ingress (load balancer)



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `cluster` (String) Identifier of the cluster. After the creation of the resource, it is not possible to update the attribute value.
- `listening_method` (String) Listening Method for apps ingress. Options are external,internal.

### Optional

- `id` (String) Unique identifier of the ingress.
