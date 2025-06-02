# Red Hat Advanced Cluster Management for Kubernetes governance policies examples

This is a set of RHACM policies intended for use during demonstrations. Don’t hesitate to use them as bolier plates or take inspiration from them to create your own.

## Description of the different policies

### Install RHACS Operator and Spin a Secured Cluster Instance
([policy-acs-secured-cluster.yaml](policy-acs-secured-cluster.yaml))
> **Warning**
> Prior to add this policy, you will need to add the StackRox cluster init bundle secrets into the hub cluster in namespace: openshift-acm-policies

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Check Cert Expiration
([policy-check-certexpiration.yaml](policy-check-certexpiration.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Install Compliance Operator
([policy-compliance-operator.yaml](policy-compliance-operator.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Limit Role Binding
([policy-limit-rolebinding.yaml](policy-limit-rolebinding.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Cluster Must Has Namespace
([policy-musthave-namespace.yaml](policy-musthave-namespace.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Network Policy DenyAll by Default
([policy-network-denyall.yaml](policy-network-denyall.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Push Cetificate in Namespaces
([policy-push-enterpriseCA.yaml](policy-push-enterpriseCA.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

### Apply Resource Quotas on Namespaces
([policy-tenant-resourcequota.yaml](policy-tenant-resourcequota.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.

 PolicySet and Placement Rules
([policyset-and-placement.yaml](policyset-and-placement.yaml))

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec quis placerat purus. Aenean viverra est eu finibus fermentum. Duis sit amet tortor vestibulum, lobortis ipsum id, viverra odio. Sed cursus ornare efficitur. Donec nisi ante, fringilla ut pharetra vestibulum, posuere ac lacus. In vitae augue a sem accumsan volutpat. Donec non nisl mollis, egestas leo eu, tincidunt magna. Suspendisse tincidunt, elit porttitor pulvinar tristique, leo justo lobortis quam, quis ornare turpis massa et libero. Aliquam odio velit, volutpat ac ullamcorper nec, dictum at justo. Nullam consectetur ligula vel mollis suscipit.
