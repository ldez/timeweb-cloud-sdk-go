# DomainRegisterNsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | Хост name-сервера. | 
**Ips** | **[]string** | Список IP-адресов name-сервера | 

## Methods

### NewDomainRegisterNsInner

`func NewDomainRegisterNsInner(host string, ips []string, ) *DomainRegisterNsInner`

NewDomainRegisterNsInner instantiates a new DomainRegisterNsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainRegisterNsInnerWithDefaults

`func NewDomainRegisterNsInnerWithDefaults() *DomainRegisterNsInner`

NewDomainRegisterNsInnerWithDefaults instantiates a new DomainRegisterNsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *DomainRegisterNsInner) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *DomainRegisterNsInner) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *DomainRegisterNsInner) SetHost(v string)`

SetHost sets Host field to given value.


### GetIps

`func (o *DomainRegisterNsInner) GetIps() []string`

GetIps returns the Ips field if non-nil, zero value otherwise.

### GetIpsOk

`func (o *DomainRegisterNsInner) GetIpsOk() (*[]string, bool)`

GetIpsOk returns a tuple with the Ips field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIps

`func (o *DomainRegisterNsInner) SetIps(v []string)`

SetIps sets Ips field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


