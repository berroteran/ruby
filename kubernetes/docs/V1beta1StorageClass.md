# Kubernetes::V1beta1StorageClass

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allow_volume_expansion** | **BOOLEAN** | AllowVolumeExpansion shows whether the storage class allow volume expand | [optional] 
**api_version** | **String** | APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#resources | [optional] 
**kind** | **String** | Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds | [optional] 
**metadata** | [**V1ObjectMeta**](V1ObjectMeta.md) | Standard object&#39;s metadata. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#metadata | [optional] 
**mount_options** | **Array&lt;String&gt;** | Dynamically provisioned PersistentVolumes of this storage class are created with these mountOptions, e.g. [\&quot;ro\&quot;, \&quot;soft\&quot;]. Not validated - mount of the PVs will simply fail if one is invalid. | [optional] 
**parameters** | **Hash&lt;String, String&gt;** | Parameters holds the parameters for the provisioner that should create volumes of this storage class. | [optional] 
**provisioner** | **String** | Provisioner indicates the type of the provisioner. | 
**reclaim_policy** | **String** | Dynamically provisioned PersistentVolumes of this storage class are created with this reclaimPolicy. Defaults to Delete. | [optional] 


