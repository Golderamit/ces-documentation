---
sidebar_position: 3
---

# List Bank Account

## 1. version control

| Version  | Date        | Description of Changes |
| -------- | ----------- | ---------------------- |
| CES V1.0 | May 3, 2023 | Initial Release        |

## 2. Overview

####  In cryptocurrency exchange system admin can get bank account list.


## 3. API

### List Bank Account Request example:

```json
{
  "SortBy": "ASC",
  "SortByColumn": "BankName",
  "SortType": "similar",
  "SearchTerm": "Like",
  "StartDate": "2023-02-08 09:12:15",
  "EndDate": "2023-05-08 09:12:15"
}
```

### List Bank Account Response example:

```json
{
   "Data": {
    "BankAccounts":[
      {
        "ID": "123e4567-e89b-12d3-a456-426614174111",
        "UserID": "123e4567-e89b-12d3-a456-426614174000",
        "ReferenceNumber": "37421575175977",
        "BankName": "Sonali Bank",
        "AccountName": "Deposite",
        "AccountNumber": "1234567890",
        "AccountHolder": "Amit Golder",
        "RoutingNumber": "5456",
        "SWIFT": "SDFSD45",
        "IBAN":"SJ5FGSD45",
        "BIC": "WI5EUR8",
        "IsPrimary": "IS_PRIMARY_TRUE",
        "CountryID": 564513164515,
        "BankAddress": "KDA 17 Khulna Bangladesh",
        "AccountHolderAddress":"Sonadanga 2nd area",
        "IsActive": "IS_ACTIVE_TRUE",
        "IsVerified": "IS_VERIFIED_FALSE",
        "CreatedAt": "2023-05-08 09:12:15",
        "UpdatedAt": "2023-05-08 09:12:15",
        "CreatedBy": "123e4567-e89b-12d3-a456-426614174025",
        "UpdatedBy": "123e4567-e89b-12d3-a456-426614174025"
      },
      {
        "ID": "123e4567-e89b-12d3-a456-426614174112",
        "UserID": "123e4567-e89b-12d3-a456-426614174001",
        "ReferenceNumber": "37421575175978",
        "BankName": "Sonali Bank",
        "AccountName": "Deposite",
        "AccountNumber": "1234567890",
        "AccountHolder": "Amit Golder",
        "RoutingNumber": "5456",
        "SWIFT": "SDFSD45",
        "IBAN":"SJ5FGSD45",
        "BIC": "WI5EUR8",
        "IsPrimary": "IS_PRIMARY_TRUE",
        "CountryID": 564513164515,
        "BankAddress": "KDA 17 Khulna Bangladesh",
        "AccountHolderAddress":"Sonadanga 2nd area",
        "IsActive": "IS_ACTIVE_TRUE",
        "IsVerified": "IS_VERIFIED_FALSE",
        "CreatedAt": "2023-05-08 09:12:15",
        "UpdatedAt": "2023-05-08 09:12:15",
        "CreatedBy": "123e4567-e89b-12d3-a456-426614174025",
        "UpdatedBy": "123e4567-e89b-12d3-a456-426614174025"
      }
    ]
   },
   "TotalPages": 1
}
```

## 4. Enum Fields
#### **IsPrimary**
&nbsp;

	IS_PRIMARY_FALSE
	IS_PRIMARY_TRUE

#### **IsActive**
&nbsp;

	IS_ACTIVE_FALSE
	IS_ACTIVE_TRUE
	
#### **IsVerified**
&nbsp;

	IS_VERIFIED_FALSE
	IS_VERIFIED_TRUE
