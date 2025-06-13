# Code examples

**Author:** Rachael Allen

## cURL example

Use this cURL command to retrieve a list of users from the local API.

### cURL command

```shell
curl http://localhost:3000/users
```

### cURL response

```shell
[
  {
    "last_name": "Smith",
    "first_name": "Ferdinand",
    "email": "f.smith@example.com",
    "id": 1
  },
  {
    "last_name": "Jones",
    "first_name": "Jill",
    "email": "j.jones@example.com",
    "id": 2
  },
  {
    "last_name": "Martinez",
    "first_name": "Marty",
    "email": "m.martinez@example.com",
    "id": 3
  },
  {
    "last_name": "Bailey",
    "first_name": "Bill",
    "email": "b.bailey@example.com",
    "id": 4
  }
]%        
```

## Postman example

Use this GET request in Postman to retrieve a list of tasks.

### Request

**Method**: GET

```shell
{base_url}/tasks
```

## Base URL

For local testing, the API base URL is: 
http://localhost:3000


### Postman response

```shell
[
    {
        "user_id": 1,
        "title": "Grocery shopping",
        "description": "eggs, bacon, gummy bears",
        "due_date": "2025-02-20T17:00",
        "warning": "-10",
        "id": 1
    },
    {
        "user_id": 1,
        "title": "Piano recital",
        "description": "Daughter's first concert appearance",
        "due_date": "2025-04-02T15:00",
        "warning": "-30",
        "id": 2
    },
    {
        "user_id": 2,
        "title": "Oil change",
        "description": "5K auto service",
        "due_date": "2025-03-10T09:00",
        "warning": "-60",
        "id": 3
    },
    {
        "user_id": 3,
        "title": "Get shots for dog",
        "description": "Annual vaccinations for poochy",
        "due_date": "2025-05-11T14:00",
        "warning": "-20",
        "id": 4
    }
]
```
