# QueryHealthPressure

- Query user pressure data with datetime condition

**Api URL：**
- ` http://xx.com/api/db/QueryHealthPressure `

**Http Request Method：**
- POST

**Params：**

| Param Name | Optional | Type     | Desc                |
| :--------- | :------- | :------- | ------------------- |
| Account    | false    | string   | user wallet address |
| DateStart  | false    | datetime | query condition     |
| DateEnd    | false    | datetime | query condition     |

 **Response Sample**

```
{
    "items": [
        {
            "buildTime": "2017-05-31T22:44:02",
            "highPressure": 118,
            "lowPressure": 55,
            "pulse": 83
        },
        {
            "buildTime": "2017-05-31T22:45:03",
            "highPressure": 119,
            "lowPressure": 61,
            "pulse": 79
        },
        {
            "buildTime": "2017-06-08T12:16:17",
            "highPressure": 151,
            "lowPressure": 98,
            "pulse": 76
        }
    ],
    "result": true,
    "error": ""
}
```

 **Response Params**

| Param Name | Type   | Desc |
| :--------- | :----- | ---- |
| result     | bool   |      |
| error      | string |      |

 **Note**

- 