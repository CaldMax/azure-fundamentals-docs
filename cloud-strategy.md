# Cloud Strategy

## Cloud Adoption Framework
- tools, documentation and proven practices for cloud adoption path
  - define strategy
    - document motivation and outcomes
    - develop business case
    - choose right first project
  - make a plan
    - digital estate
    - initial alignment
    - skill plan
    - cloud adoption plan
  - ready organization
    - Azure setup
    - Azure landing zone
    - expand zone
    - start with best practice
  - adopt the cloud
    - migrate workloads
    - migrate scenarios
    - check best practices
    - process improvements
  - innovate
    - business value consensus
    - use innovation guide and verify best practices
    - feedback loops
  - govern
    - methodology
    - benchmark of governance
    - manage and improvements

## Subscription governance
- Billing
  - 1 billing report per sub or multiple per department
  - resource tags
- Control access

## Azure RBAC
- applied to a scope = resource / set of resources / subscription / management group
- when?
  - assign different roles within a single subscription to different groups of people
- enforced by actions done within ARM
- application security not handled

## Locks
- prevent resources from accidental delete or change (CanNotDelete / ReadOnly)
- can combined with Azure Blueprints to make locks not accidentally removable

## Tags
- metadata formed by key and value pairs
- useful for:
  - resource management
  - cost management
  - operations management
  - security
  - governnce and compliance
  - optimization

## Azure policy
- definition of a policy (allowed SKUs for VMs, allowed regions, ...)
- assign definition to resources (scope can be management group, single subscription, resource or group of )
- review and evaluate
- can be grouped into initiatives

## Azure Blueprints
- can be defined to replicate a set of governance tools and standard resources required for each subscription
  - role assignments
  - policies
  - ARM templates
  - resource groups
- versioned
- composed by single artifatcs


