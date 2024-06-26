# QcWriteApi.WriteApiApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sendTransaction**](WriteApiApi.md#sendTransaction) | **POST** /transactions | Send Transaction



## sendTransaction

> TransactionSummaryResponse sendTransaction(opts)

Send Transaction

### Example

```javascript
import QcWriteApi from 'qc_write_api';

let apiInstance = new QcWriteApi.WriteApiApi();
let opts = {
  'sendTransactionRequest': new QcWriteApi.SendTransactionRequest() // SendTransactionRequest | 
};
apiInstance.sendTransaction(opts, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendTransactionRequest** | [**SendTransactionRequest**](SendTransactionRequest.md)|  | [optional] 

### Return type

[**TransactionSummaryResponse**](TransactionSummaryResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

