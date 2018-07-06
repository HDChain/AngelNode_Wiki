# GetAccountList

- Get user account list in database

**Api URL：**
- ` http://xx.com/api/db/GetAccountList `

**Http Request Method：**
- Get

**Params：**

| Param Name | Optional | Type | Desc |
| :--------- | :------- | :--- | ---- |

 **Response Sample**

```
[
    {
        "Id": 1,
        "Account": "0x975868c4032B1d2315995AD65fB87F5dd23595e7",
        "FileKey": "MIIBIDANBgkqhkiG9w0BAQEFAAOCAQ0AMIIBCAKCAQEA0hvQXEQKSyXd6Y+b4I45Zvrkw3J/L4LYlwegCmo5ni6UPUwrBdyE4lncQa3lNToyDkY4inX2b9TQ5l/GxXREvJKlX82RXiDjKdHCNwZxzkmZHi05NJvGXQLEzowvZUuy55aw9/xm6UOqX7nkCCN6PAN17h0WeLDVeO6hVJgHf0Z8s2T3FKwoxXk5uWdsSrnrKUW9EhSJLu/1XI6bTkYunORvsYUiwZ7hcWTqy9gjiA6oSC+52R+n7zOnTmjE/BOYqshO3umzaLVGwe+zZiPL6qNBNUYRMuDaDzx6fADOKVS+lffdM/Ov8F85HocjQe1mMoYtyFs2e+TxGi0aBr/gxQIBAw==",
        "ContractAddress": "0x236a6142e9a74f165d08403562973149128a147d",
        "LastSyncTime": "2018-07-06T07:17:01.18"
    }
]
```

 **Response Params**

| Param Name      | Type     | Desc                       |
| :-------------- | :------- | -------------------------- |
| Id              | int      | db row id                  |
| Account         | string   | user wallet address        |
| FileKey         | string   | user data rsa public key   |
| ContractAddress | string   | user data contract address |
| LastSyncTime    | datetime | user data last sync time   |

 **Note**

- 