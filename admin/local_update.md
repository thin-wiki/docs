
## 请求URL
- `http://localhost:9887/api/admin/storage/local/{storageId}`

## 请求方式
- PUT
- application/json

## 请求示例

``` json
{
    "name": "Github 主存储", 
    "description": "Github 主存储", 
    "basePath": "files"
}
```

## 请求参数

|参数名|类型|说明|
|:-----  |:-----|-----|
|storageId |string   | 记录id，请求URL中的{storageId}  |
|name |string   | 名字  | 
|description |string   | 描述  |
|basePath |string   | 仓库中的文件基本目录  |

## 返回示例

``` json
{
    "code": 0, 
    "msg": "success"
}
```

## 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|code |int   |返回码，0-正常，1-异常  |
|msg |string   | 返回消息  |




