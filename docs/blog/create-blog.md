---
sidebar_position: 14
---

# Create Blog

## 1. version control

| Version  | Date        | Description of Changes |
| -------- | ----------- | ---------------------- |
| CES V1.0 | May 3, 2023 | Initial Release        |

## 2. Overview

#### In cryptocurrency exchange system blog can be created in two way.
##### i.  Admin can be create
##### ii. User can be create 


## 3. API

### Create Blog Request example:

```json
{
  "Title": "BdNews",
  "Category": "News",
  "Content": "content is a",
  "IsFeatured": "ACTIVE",
  "ImageUrl": "https://demo.com/storage/images/coin-icons/default.jpg",
  "IsPublished": "ACTIVE"
}
```

### Create Blog Response example:

```json
{
  "Data": {
    "Blog": {
            "ID": "123e4567-e89b-12d3-a456-426614174111",
            "UserID": "123e4567-e89b-12d3-a456-426614174000", 
            "CategoryID": "123e4567-e89b-12d3-a456-426614174000",	
            "Title": "BdNews",
            "Category": "News",
            "Content": "content is a",
            "IsFeatured": "ACTIVE",
            "ImageUrl": "https://demo.com/storage/images/coin-icons/default.jpg",
            "IsPublished": "ACTIVE",
            "Slug": "BdNews",
            "CreatedAt": "2023-05-08 09:12:15",
            "UpdatedAt": "2023-05-08 09:12:15",
            "CreatedBy": "123e4567-e89b-12d3-a456-426614174025",
            "UpdatedBy": "123e4567-e89b-12d3-a456-426614174025"
           }
         }
}
```
