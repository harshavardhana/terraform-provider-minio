---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "minio_iam_group Resource - terraform-provider-minio"
subcategory: ""
description: |-
  
---

# minio_iam_group (Resource)



## Example Usage

```terraform
resource "minio_iam_group" "developer" {
  name = "developer"
}

output "minio_user_group" {
  value = minio_iam_group.developer.group_name
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String)

### Optional

- **disable_group** (Boolean) Disable group
- **force_destroy** (Boolean) Delete group even if it has non-Terraform-managed members
- **id** (String) The ID of this resource.

### Read-Only

- **group_name** (String)

