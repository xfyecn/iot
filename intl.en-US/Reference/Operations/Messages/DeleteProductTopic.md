# DeleteProductTopic {#reference_qyn_cjd_xdb .reference}

You can call this operation to delete a specified topic category.

## Request parameters {#section_ycv_4g5_xdb .section}

|Name|Type|Required|Description|
|:---|:---|:-------|:----------|
|Action|String|Yes|The operation that you want to perform. Set the value to DeleteProductTopic.|
|TopicId|Long|Yes|The identifier of the topic category that you want to delete.|

## Response parameters {#section_jbl_yg5_xdb .section}

|Name|Type|Description |
|:---|:---|:-----------|
|RequestId|String|The GUID generated by Alibaba Cloud for the request.|
|Success|Boolean|Indicates whether the call is successful. A value of true indicates that the call is successful. A value of false indicates that the call has failed.|
|ErrorMessage|String|The error message returned when the call fails.|

## Examples {#section_vhq_dh5_xdb .section}

**Request example**

```
https://iot.cn-shanghai.aliyuncs.com/?Action=DeleteProductTopic
 &TopicId=10000
 &common_parameters
```

**Response example**

```
{
    "RequestId":"FCC27691-9151-4B93-9622-9C90F30542EC",
    "Success":true
}
```
