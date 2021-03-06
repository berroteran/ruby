# Kubernetes::V1alpha1PriorityClass

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_version** | **String** | APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#resources | [optional] 
**description** | **String** | description is an arbitrary string that usually provides guidelines on when this priority class should be used. | [optional] 
**global_default** | **BOOLEAN** | globalDefault specifies whether this PriorityClass should be considered as the default priority for pods that do not have any priority class. | [optional] 
**kind** | **String** | Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase. More info: https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds | [optional] 
**metadata** | [**V1ObjectMeta**](V1ObjectMeta.md) | Standard object&#39;s metadata. More info: http://releases.k8s.io/HEAD/docs/devel/api-conventions.md#metadata | [optional] 
**value** | **Integer** | The value of this priority class. This is the actual priority that pods receive when they have the name of this class in their pod spec. | 


