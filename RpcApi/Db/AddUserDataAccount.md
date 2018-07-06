# AddUserDataAccount

- Api new user account 

data service fetch user data internal

**Api URL：**
- ` http://xx.com/api/db/AddUserDataAccount `

**Http Request Method：**
- POST

**Params：**

| Param Name      | Optional | Type   | Desc                     |
| :-------------- | :------- | :----- | ------------------------ |
| ContractAddress | false    | string | data contract address    |
| Account         | false    | string | user wallet address      |
| FileKey         | false    | string | user data rsa public key |

 **Response Sample**

```
{
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


