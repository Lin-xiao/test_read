# virtual machine 

#### 1. `开机/关机`

`GET` `https://baidu/v1/pve/opdasdaen/dasda/{id}`

**Request paramerter**

| Parameter | Description         | Required | Type   |
| --------- | ------------------- | -------- | ------ |
| id        | 测试                | YES      | string |
| status    | 0：测试     1：测试 | YES      | string |

**Responses**

```json
{
    "codedasda":0,
    "dataasda":true,
    "msgdasda":"success"
}
```

**code**

| 错误码 | 错误描述     |
| ------ | ------------ |
| 1001   | 测试不足     |
| 6000   | 测试中       |
| 6001   | 测试中       |
| 6002   | 测试         |
| 6003   | 测试余额不足 |

#### 2.`重启`

`POST ` ``https://www.baidu.com/v1/das/opedasdn/reboot``

**Request paramerter**

| Parameter | Description | Required | Type   |
| --------- | ----------- | -------- | ------ |
| id        | 主机ID      | YES      | string |

**Responses**

```json
{
    "code":0,
    "data":true,
    "msg":"success"
}
```

**code**

| 错误码 | 错误描述           |
| ------ | ------------------ |
| 70022  | 测试不能重启       |
| 70032  | 测试可用，不能重启 |
| 70042  | 测试运行，不能重启 |

