**Desc：**

- Api Name

**Api URL：**
- ` http://xx.com/api/user/register `

**Http Request Method：**
- POST

**Params：**

| Param Name | Optional | Type   | Desc      |
| :--------- | :------- | :----- | --------- |
| username   | true     | string | user name |
| password   | true     | string |           |
| name       | true     | string |           |

 **Response Sample**

```
  {
    "error_code": 0,
    "data": {
      "uid": "1",
      "username": "12154545",
      "name": "Tom",
      "groupid": 2 ,
      "reg_time": "1436864169",
      "last_login_time": "0",
    }
  }
```

 **Response Params**

| Param Name | Type   | Desc |
| :--------- | :----- | ---- |
| result     | bool   |      |
| error      | string |      |

 **Note**

- 


