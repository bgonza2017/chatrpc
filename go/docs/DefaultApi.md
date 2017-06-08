# \DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/bgonza2017/chatrpc/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLobbyUserList**](DefaultApi.md#GetLobbyUserList) | **Get** /lobby | 
[**Join**](DefaultApi.md#Join) | **Post** /lobby | 


# **GetLobbyUserList**
> []NewUser GetLobbyUserList()



get user list


### Parameters
This endpoint does not need any parameter.

### Return type

[**[]NewUser**](NewUser.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **Join**
> User Join($user)



lobby


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user** | [**NewUser**](NewUser.md)| add user to lobby | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

