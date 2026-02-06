---
permalink: /1.132.1/operator/v1alpha1/extension/
---

# operator.v1alpha1.extension

"Extension describes a Gardener extension."

## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withResources(resources)`](#fn-specwithresources)
  * [`fn withResourcesMixin(resources)`](#fn-specwithresourcesmixin)
  * [`obj spec.deployment`](#obj-specdeployment)
    * [`obj spec.deployment.admission`](#obj-specdeploymentadmission)
      * [`fn withValues(values)`](#fn-specdeploymentadmissionwithvalues)
      * [`obj spec.deployment.admission.runtimeCluster`](#obj-specdeploymentadmissionruntimecluster)
        * [`obj spec.deployment.admission.runtimeCluster.helm`](#obj-specdeploymentadmissionruntimeclusterhelm)
          * [`obj spec.deployment.admission.runtimeCluster.helm.ociRepository`](#obj-specdeploymentadmissionruntimeclusterhelmocirepository)
            * [`fn withDigest(digest)`](#fn-specdeploymentadmissionruntimeclusterhelmocirepositorywithdigest)
            * [`fn withRef(ref)`](#fn-specdeploymentadmissionruntimeclusterhelmocirepositorywithref)
            * [`fn withRepository(repository)`](#fn-specdeploymentadmissionruntimeclusterhelmocirepositorywithrepository)
            * [`fn withTag(tag)`](#fn-specdeploymentadmissionruntimeclusterhelmocirepositorywithtag)
            * [`obj spec.deployment.admission.runtimeCluster.helm.ociRepository.pullSecretRef`](#obj-specdeploymentadmissionruntimeclusterhelmocirepositorypullsecretref)
              * [`fn withName(name)`](#fn-specdeploymentadmissionruntimeclusterhelmocirepositorypullsecretrefwithname)
      * [`obj spec.deployment.admission.virtualCluster`](#obj-specdeploymentadmissionvirtualcluster)
        * [`obj spec.deployment.admission.virtualCluster.helm`](#obj-specdeploymentadmissionvirtualclusterhelm)
          * [`obj spec.deployment.admission.virtualCluster.helm.ociRepository`](#obj-specdeploymentadmissionvirtualclusterhelmocirepository)
            * [`fn withDigest(digest)`](#fn-specdeploymentadmissionvirtualclusterhelmocirepositorywithdigest)
            * [`fn withRef(ref)`](#fn-specdeploymentadmissionvirtualclusterhelmocirepositorywithref)
            * [`fn withRepository(repository)`](#fn-specdeploymentadmissionvirtualclusterhelmocirepositorywithrepository)
            * [`fn withTag(tag)`](#fn-specdeploymentadmissionvirtualclusterhelmocirepositorywithtag)
            * [`obj spec.deployment.admission.virtualCluster.helm.ociRepository.pullSecretRef`](#obj-specdeploymentadmissionvirtualclusterhelmocirepositorypullsecretref)
              * [`fn withName(name)`](#fn-specdeploymentadmissionvirtualclusterhelmocirepositorypullsecretrefwithname)
    * [`obj spec.deployment.extension`](#obj-specdeploymentextension)
      * [`fn withInjectGardenKubeconfig(injectGardenKubeconfig)`](#fn-specdeploymentextensionwithinjectgardenkubeconfig)
      * [`fn withPolicy(policy)`](#fn-specdeploymentextensionwithpolicy)
      * [`fn withRuntimeClusterValues(runtimeClusterValues)`](#fn-specdeploymentextensionwithruntimeclustervalues)
      * [`fn withValues(values)`](#fn-specdeploymentextensionwithvalues)
      * [`obj spec.deployment.extension.helm`](#obj-specdeploymentextensionhelm)
        * [`obj spec.deployment.extension.helm.ociRepository`](#obj-specdeploymentextensionhelmocirepository)
          * [`fn withDigest(digest)`](#fn-specdeploymentextensionhelmocirepositorywithdigest)
          * [`fn withRef(ref)`](#fn-specdeploymentextensionhelmocirepositorywithref)
          * [`fn withRepository(repository)`](#fn-specdeploymentextensionhelmocirepositorywithrepository)
          * [`fn withTag(tag)`](#fn-specdeploymentextensionhelmocirepositorywithtag)
          * [`obj spec.deployment.extension.helm.ociRepository.pullSecretRef`](#obj-specdeploymentextensionhelmocirepositorypullsecretref)
            * [`fn withName(name)`](#fn-specdeploymentextensionhelmocirepositorypullsecretrefwithname)
      * [`obj spec.deployment.extension.seedSelector`](#obj-specdeploymentextensionseedselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specdeploymentextensionseedselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specdeploymentextensionseedselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specdeploymentextensionseedselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specdeploymentextensionseedselectorwithmatchlabelsmixin)
        * [`obj spec.deployment.extension.seedSelector.matchExpressions`](#obj-specdeploymentextensionseedselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specdeploymentextensionseedselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specdeploymentextensionseedselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specdeploymentextensionseedselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specdeploymentextensionseedselectormatchexpressionswithvaluesmixin)
  * [`obj spec.resources`](#obj-specresources)
    * [`fn withAutoEnable(autoEnable)`](#fn-specresourceswithautoenable)
    * [`fn withAutoEnableMixin(autoEnable)`](#fn-specresourceswithautoenablemixin)
    * [`fn withClusterCompatibility(clusterCompatibility)`](#fn-specresourceswithclustercompatibility)
    * [`fn withClusterCompatibilityMixin(clusterCompatibility)`](#fn-specresourceswithclustercompatibilitymixin)
    * [`fn withKind(kind)`](#fn-specresourceswithkind)
    * [`fn withPrimary(primary)`](#fn-specresourceswithprimary)
    * [`fn withReconcileTimeout(reconcileTimeout)`](#fn-specresourceswithreconciletimeout)
    * [`fn withType(type)`](#fn-specresourceswithtype)
    * [`fn withWorkerlessSupported(workerlessSupported)`](#fn-specresourceswithworkerlesssupported)
    * [`obj spec.resources.lifecycle`](#obj-specresourceslifecycle)
      * [`fn withDelete(delete)`](#fn-specresourceslifecyclewithdelete)
      * [`fn withMigrate(migrate)`](#fn-specresourceslifecyclewithmigrate)
      * [`fn withReconcile(reconcile)`](#fn-specresourceslifecyclewithreconcile)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of Extension

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"Spec contains the specification of this extension."

### fn spec.withResources

```ts
withResources(resources)
```

"Resources is a list of combinations of kinds (DNSRecord, Backupbucket, ...) and their actual types\n(aws-route53, gcp)."

### fn spec.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources is a list of combinations of kinds (DNSRecord, Backupbucket, ...) and their actual types\n(aws-route53, gcp)."

**Note:** This function appends passed data to existing values

## obj spec.deployment

"Deployment contains deployment configuration for an extension and it's admission controller."

## obj spec.deployment.admission

"AdmissionDeployment contains the deployment configuration for an admission controller."

### fn spec.deployment.admission.withValues

```ts
withValues(values)
```

"Values are the deployment values. The values will be applied to both admission deployments."

## obj spec.deployment.admission.runtimeCluster

"RuntimeCluster is the deployment configuration for the admission in the runtime cluster. The runtime deployment\nis responsible for creating the admission controller in the runtime cluster."

## obj spec.deployment.admission.runtimeCluster.helm

"Helm contains the specification for a Helm deployment."

## obj spec.deployment.admission.runtimeCluster.helm.ociRepository

"OCIRepository defines where to pull the chart from."

### fn spec.deployment.admission.runtimeCluster.helm.ociRepository.withDigest

```ts
withDigest(digest)
```

"Digest of the image to pull, takes precedence over tag.\nThe value should be in the format 'sha256:<HASH>'."

### fn spec.deployment.admission.runtimeCluster.helm.ociRepository.withRef

```ts
withRef(ref)
```

"Ref is the full artifact Ref and takes precedence over all other fields."

### fn spec.deployment.admission.runtimeCluster.helm.ociRepository.withRepository

```ts
withRepository(repository)
```

"Repository is a reference to an OCI artifact repository."

### fn spec.deployment.admission.runtimeCluster.helm.ociRepository.withTag

```ts
withTag(tag)
```

"Tag is the image tag to pull."

## obj spec.deployment.admission.runtimeCluster.helm.ociRepository.pullSecretRef

"PullSecretRef is a reference to a secret containing the pull secret.\nThe secret must be of type `kubernetes.io/dockerconfigjson` and must be located in the `garden` namespace.\nFor usage in the gardenlet, the secret must have the label `gardener.cloud/role=helm-pull-secret`."

### fn spec.deployment.admission.runtimeCluster.helm.ociRepository.pullSecretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.deployment.admission.virtualCluster

"VirtualCluster is the deployment configuration for the admission deployment in the garden cluster. The garden deployment\ninstalls necessary resources in the virtual garden cluster e.g. RBAC that are necessary for the admission controller."

## obj spec.deployment.admission.virtualCluster.helm

"Helm contains the specification for a Helm deployment."

## obj spec.deployment.admission.virtualCluster.helm.ociRepository

"OCIRepository defines where to pull the chart from."

### fn spec.deployment.admission.virtualCluster.helm.ociRepository.withDigest

```ts
withDigest(digest)
```

"Digest of the image to pull, takes precedence over tag.\nThe value should be in the format 'sha256:<HASH>'."

### fn spec.deployment.admission.virtualCluster.helm.ociRepository.withRef

```ts
withRef(ref)
```

"Ref is the full artifact Ref and takes precedence over all other fields."

### fn spec.deployment.admission.virtualCluster.helm.ociRepository.withRepository

```ts
withRepository(repository)
```

"Repository is a reference to an OCI artifact repository."

### fn spec.deployment.admission.virtualCluster.helm.ociRepository.withTag

```ts
withTag(tag)
```

"Tag is the image tag to pull."

## obj spec.deployment.admission.virtualCluster.helm.ociRepository.pullSecretRef

"PullSecretRef is a reference to a secret containing the pull secret.\nThe secret must be of type `kubernetes.io/dockerconfigjson` and must be located in the `garden` namespace.\nFor usage in the gardenlet, the secret must have the label `gardener.cloud/role=helm-pull-secret`."

### fn spec.deployment.admission.virtualCluster.helm.ociRepository.pullSecretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.deployment.extension

"ExtensionDeployment contains the deployment configuration an extension."

### fn spec.deployment.extension.withInjectGardenKubeconfig

```ts
withInjectGardenKubeconfig(injectGardenKubeconfig)
```

"InjectGardenKubeconfig controls whether a kubeconfig to the garden cluster should be injected into workload\nresources."

### fn spec.deployment.extension.withPolicy

```ts
withPolicy(policy)
```

"Policy controls how the controller is deployed. It defaults to 'OnDemand'."

### fn spec.deployment.extension.withRuntimeClusterValues

```ts
withRuntimeClusterValues(runtimeClusterValues)
```

"RuntimeClusterValues are the deployment values for the extension deployment running in the runtime garden cluster."

### fn spec.deployment.extension.withValues

```ts
withValues(values)
```

"Values are the deployment values used in the creation of the ControllerDeployment in the virtual garden cluster."

## obj spec.deployment.extension.helm

"Helm contains the specification for a Helm deployment."

## obj spec.deployment.extension.helm.ociRepository

"OCIRepository defines where to pull the chart from."

### fn spec.deployment.extension.helm.ociRepository.withDigest

```ts
withDigest(digest)
```

"Digest of the image to pull, takes precedence over tag.\nThe value should be in the format 'sha256:<HASH>'."

### fn spec.deployment.extension.helm.ociRepository.withRef

```ts
withRef(ref)
```

"Ref is the full artifact Ref and takes precedence over all other fields."

### fn spec.deployment.extension.helm.ociRepository.withRepository

```ts
withRepository(repository)
```

"Repository is a reference to an OCI artifact repository."

### fn spec.deployment.extension.helm.ociRepository.withTag

```ts
withTag(tag)
```

"Tag is the image tag to pull."

## obj spec.deployment.extension.helm.ociRepository.pullSecretRef

"PullSecretRef is a reference to a secret containing the pull secret.\nThe secret must be of type `kubernetes.io/dockerconfigjson` and must be located in the `garden` namespace.\nFor usage in the gardenlet, the secret must have the label `gardener.cloud/role=helm-pull-secret`."

### fn spec.deployment.extension.helm.ociRepository.pullSecretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.deployment.extension.seedSelector

"SeedSelector contains an optional label selector for seeds. Only if the labels match then this controller will be\nconsidered for a deployment.\nAn empty list means that all seeds are selected."

### fn spec.deployment.extension.seedSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.deployment.extension.seedSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.deployment.extension.seedSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.deployment.extension.seedSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.deployment.extension.seedSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.deployment.extension.seedSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.deployment.extension.seedSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.deployment.extension.seedSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.deployment.extension.seedSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.resources

"Resources is a list of combinations of kinds (DNSRecord, Backupbucket, ...) and their actual types\n(aws-route53, gcp)."

### fn spec.resources.withAutoEnable

```ts
withAutoEnable(autoEnable)
```

"AutoEnable determines if this resource is automatically enabled for shoot or seed clusters, or both.\nThis field can only be set for resources of kind \"Extension\"."

### fn spec.resources.withAutoEnableMixin

```ts
withAutoEnableMixin(autoEnable)
```

"AutoEnable determines if this resource is automatically enabled for shoot or seed clusters, or both.\nThis field can only be set for resources of kind \"Extension\"."

**Note:** This function appends passed data to existing values

### fn spec.resources.withClusterCompatibility

```ts
withClusterCompatibility(clusterCompatibility)
```

"ClusterCompatibility defines the compatibility of this resource with different cluster types.\nIf compatibility is not specified, it will be defaulted to 'shoot'.\nThis field can only be set for resources of kind \"Extension\"."

### fn spec.resources.withClusterCompatibilityMixin

```ts
withClusterCompatibilityMixin(clusterCompatibility)
```

"ClusterCompatibility defines the compatibility of this resource with different cluster types.\nIf compatibility is not specified, it will be defaulted to 'shoot'.\nThis field can only be set for resources of kind \"Extension\"."

**Note:** This function appends passed data to existing values

### fn spec.resources.withKind

```ts
withKind(kind)
```

"Kind is the resource kind, for example \"OperatingSystemConfig\"."

### fn spec.resources.withPrimary

```ts
withPrimary(primary)
```

"Primary determines if the controller backed by this ControllerRegistration is responsible for the extension\nresource's lifecycle. This field defaults to true. There must be exactly one primary controller for this kind/type\ncombination. This field is immutable."

### fn spec.resources.withReconcileTimeout

```ts
withReconcileTimeout(reconcileTimeout)
```

"ReconcileTimeout defines how long Gardener should wait for the resource reconciliation.\nThis field is defaulted to 3m0s when kind is \"Extension\"."

### fn spec.resources.withType

```ts
withType(type)
```

"Type is the resource type, for example \"coreos\" or \"ubuntu\"."

### fn spec.resources.withWorkerlessSupported

```ts
withWorkerlessSupported(workerlessSupported)
```

"WorkerlessSupported specifies whether this ControllerResource supports Workerless Shoot clusters.\nThis field is only relevant when kind is \"Extension\"."

## obj spec.resources.lifecycle

"Lifecycle defines a strategy that determines when different operations on a ControllerResource should be performed.\nThis field is defaulted in the following way when kind is \"Extension\".\n Reconcile: \"AfterKubeAPIServer\"\n Delete: \"BeforeKubeAPIServer\"\n Migrate: \"BeforeKubeAPIServer\

### fn spec.resources.lifecycle.withDelete

```ts
withDelete(delete)
```

"Delete defines the strategy during deletion."

### fn spec.resources.lifecycle.withMigrate

```ts
withMigrate(migrate)
```

"Migrate defines the strategy during migration."

### fn spec.resources.lifecycle.withReconcile

```ts
withReconcile(reconcile)
```

"Reconcile defines the strategy during reconciliation."