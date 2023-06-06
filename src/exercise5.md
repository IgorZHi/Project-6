# Swagger


### 1. GET​/api​/v1​/Activities

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 
 {
    "id": 1,
    "title": "Activity 1",
    "dueDate": "2023-06-05T09:21:43.2783785+00:00",
    "completed": false
  },

### 2. POST/api​/v1​/Activities

- HTTP-метод; **POST**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities
- Заголовки запроса;  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 1,
  "title": "string",
  "dueDate": "2023-06-05T08:26:40.346Z",
  "completed": true
}
- Статус-код ответа; 200
- Тело ответа (при наличии). 
{
  "id": 1,
  "title": "string",
  "dueDate": "2023-06-05T08:26:40.346Z",
  "completed": true
}



### 3. POST/api​/v1​/Activities

- HTTP-метод; **POST**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities
- Заголовки запроса;  -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 1111111111111111111111111111111,
  "title": "string",
  "dueDate": "2023-06-05T08:26:40.346Z",
  "completed": true
}
- Статус-код ответа; 400
- Тело ответа (при наличии). 
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-d9c30a95c0b8fd46bfb8b589969819a4-a8a6d9fa0ad79a4d-00",
  "errors": {
    "$.id": [
      "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 0 | BytePositionInLine: 27."
    ]
  }
}



### 4. GET​/api​/v1​/Activities/{2}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/2
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 
{
  "id": 2,
  "title": "Activity 2",
  "dueDate": "2023-06-05T10:38:45.1659336+00:00",
  "completed": true
}



### 5. GET​/api​/v1​/Activities/{22222222222222222222}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/22222222222222222222
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии). 
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-42be8d239b191c45a9b1ba7f74d8d53e-0936800dce2e3246-00",
  "errors": {
    "id": [
      "The value '22222222222222222222' is not valid."
    ]
  }}



### 6. PUT​/api​/v1​/Activities/{3}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/3
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-05T08:52:41.073Z",
  "completed": true
}
- Статус-код ответа; 200
- Тело ответа (при наличии). 
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-05T08:52:41.073Z",
  "completed": true
}



### 7. PUT​/api​/v1​/Activities/{3}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/3
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 333333333333333333333333333333,
  "title": "string",
  "dueDate": "2023-06-05T08:52:41.073Z",
  "completed": true
}
- Статус-код ответа; 400
- Тело ответа (при наличии). 
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-07bd39b11f8e814a9861b003bd0d2fe5-1a706aa2975cfd4e-00",
  "errors": {
    "$.id": [
      "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 0 | BytePositionInLine: 27."
    ]
  }
}


### 8. DELETE​/api​/v1​/Activities/{4}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/4
- Заголовки запроса;    -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 



### 9. DELETE​/api​/v1​/Activities/{44444444444444444444}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Activities/44444444444444444444
- Заголовки запроса;    -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-2aa0b36022248847ba4537b2e98cfae9-2fb161f4b0cb7b4e-00",
  "errors": {
    "id": [
      "The value '44444444444444444444' is not valid."
    ]
  }}



### 10. GET​/api​/v1​/Authors

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 

  {
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
  },




### 11. POST​/api​/v1​/Authors

- HTTP-метод; **POST**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id":11,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа; 200
- Тело ответа (при наличии). 
{
  "id": 11,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}



### 12. GET​/api/v1/Authors/authors/books/{12}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/{12}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" 
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 
[
  {
    "id": 31,
    "idBook": 12,
    "firstName": "First Name 31",
    "lastName": "Last Name 31"
  },
  {
    "id": 32,
    "idBook": 12,
    "firstName": "First Name 32",
    "lastName": "Last Name 32"
  }
]



### 13. GET​/api/v1/Authors/authors/books/{12121212121212121212}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/{12121212121212121212}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" 
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии). 
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-8fa04458e262d54196865ed971496cff-935f256b0b660747-00",
  "errors": {
    "idBook": [
      "The value '12121212121212121212' is not valid."
    ]
  }
}



### 14. GET​/api/v1/Authors/{14}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/{14}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" 
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 14,
  "idBook": 5,
  "firstName": "First Name 14",
  "lastName": "Last Name 14"
}



### 15. GET​/api/v1/Authors/{15151515151515151515}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/{15151515151515151515}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" 
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-077d5c4fe6b09b45b1ec3cda13504caf-5f3ff102561d8448-00",
  "errors": {
    "id": [
      "The value '15151515151515151515' is not valid."
    ]
  }
}



### 16. PUT​/api/v1/Authors/{16}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/{16}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии);
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
} 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}




### 17. PUT​/api/v1/Authors/{17171717171717171717}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/{17171717171717171717}
- Заголовки запроса;-H  "accept: text/plain; v=1.0" 
- Тело запроса (при наличии); 
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-e572b7a807a896459ca36ebd5fd0fce9-0266c9c3cc6be044-00",
  "errors": {
    "id": [
      "The value '17171717171717171717' is not valid."
    ]
  }
}




### 18. DELETE​/api​/v1​/Authors/{18}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/18
- Заголовки запроса;    -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии). 



### 19. DELETE​/api​/v1​/Authors/{19191919191919191919}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Authors/19191919191919191919
- Заголовки запроса;    -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии). 
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-069c8d4cbb146b4bbe42fd10e2f38dda-1f3400569b352e41-00",
  "errors": {
    "id": [
      "The value '19191919191919191919' is not valid."
    ]
  }
}




### 20. GET/api/v1/Books

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books
- Заголовки запроса; -H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).

  {
    "id": 1,
    "title": "Book 1",
    "description": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "pageCount": 100,
    "excerpt": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
    "publishDate": "2023-06-04T11:32:04.7741201+00:00"
  } 



### 21. POST/api/v1/Books

- HTTP-метод; **POST**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books
- Заголовки запроса;-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 21,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-05T11:35:28.458Z"
}
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 21,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-05T11:35:28.458Z"
}



### 22. GET/api/v1/Books/{22}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/22
- Заголовки запроса; -H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 22,
  "title": "Book 22",
  "description": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
  "pageCount": 2200,
  "excerpt": "Lorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\nLorem lorem lorem. Lorem lorem lorem. Lorem lorem lorem.\n",
  "publishDate": "2023-05-14T11:39:12.7267111+00:00"
}



### 23. GET/api/v1/Books/{232323232323}

- HTTP-метод; **GET**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/232323232323
- Заголовки запроса; -H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-ae319f0beaa93344b9a7370cc3c26a08-910c43d3daeb8047-00",
  "errors": {
    "id": [
      "The value '232323232323' is not valid."
    ]
  }
}



### 24. PUT/api/v1/Books/{24}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/24
- Заголовки запроса;-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-05T11:43:14.503Z"
}
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-05T11:43:14.503Z"
}



### 25. PUT/api/v1/Books/{252525252525}

- HTTP-метод; **PUT**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/252525252525
- Заголовки запроса;-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-05T11:43:14.503Z"
}
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-3604106677edc54d9b14d8e681ce1690-0b865e615d577742-00",
  "errors": {
    "id": [
      "The value '252525252525' is not valid."
    ]
  }
}



### 26. DELETE/api/v1/Books/{26}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/26
- Заголовки запроса;-H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).



### 27. DELETE/api/v1/Books/{272727272727}

- HTTP-метод; **DELETE**
- Полный URL запроса; https://fakerestapi.azurewebsites.net/api/v1/Books/272727272727
- Заголовки запроса;-H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-b9141b9ad72c964d97ca15c5332572b2-405f3a19efba3d46-00",
  "errors": {
    "id": [
      "The value '272727272727' is not valid."
    ]
  }
}



### 28. GET/api/v1/CoverPhotos

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
  {
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
  },



### 29. POST/api/v1/CoverPhotos

- HTTP-метод; **POST**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии);
{
  "id": 29,
  "idBook": 0,
  "url": "string"
} 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 29,
  "idBook": 0,
  "url": "string"
}



### 30. GET/api/v1/CoverPhotos/books/covers/{30}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/{30}
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
[
  {
    "id": 30,
    "idBook": 30,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 30&w=250&h=350"
  }
]



### 31.GET/api/v1/CoverPhotos/books/covers/{313131313131}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/{313131313131}
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-a885df2c9cba6a43920f1df8aab52772-c4dcc071d9b21846-00",
  "errors": {
    "idBook": [
      "The value '313131313131' is not valid."
    ]
  }
}



### 32.GET/api/v1/CoverPhotos/{32}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/{313131313131}
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 32,
  "idBook": 32,
  "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 32&w=250&h=350"
}



### 33.GET/api/v1/CoverPhotos/{333333333333}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/{333333333333}
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-8cc011dcd6be8445902a78ca6e7f6263-80e532407addcd4e-00",
  "errors": {
    "id": [
      "The value '333333333333' is not valid."
    ]
  }
}



### 34. PUT/api/v1/CoverPhotos/{34}

- HTTP-метод; **PUT**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/34
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии);
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}



### 35. PUT/api/v1/CoverPhotos/{353535353535}

- HTTP-метод; **PUT**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/353535353535
- Заголовки запроса;-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии);
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-61e3b26a8e72a74f9a841ef519dcb487-0da71c05a0acae40-00",
  "errors": {
    "id": [
      "The value '353535353535' is not valid."
    ]
  }
}



### 36. DELETE/api/v1/CoverPhotos/{36}

- HTTP-метод; **DELETE**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/36
- Заголовки запроса;-H  "accept: */*"
- Тело запроса (при наличии);
- Статус-код ответа; 200
- Тело ответа (при наличии).



### 37. DELETE/api/v1/CoverPhotos/{373737373737}

- HTTP-метод; **DELETE**
- Полный URL запроса;https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/373737373737
- Заголовки запроса;-H  "accept: */*"
- Тело запроса (при наличии);
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-1f618ee69e23314babade2ad83c83c1c-5df61ef0cfed384e-00",
  "errors": {
    "id": [
      "The value '373737373737' is not valid."
    ]
  }
}



### 38.GET/api/v1/Users

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users
- Заголовки запроса;-H  "accept: text/plain; v=1.0"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
  {
    "id": 1,
    "userName": "User 1",
    "password": "Password1"
  },



### 39.POST/api/v1/Users

- HTTP-метод; **POST**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users
- Заголовки запроса;-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 39,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа; 200
- Тело ответа (при наличии).  
{
  "id": 39,
  "userName": "string",
  "password": "string"
}



### 40.GET/api/v1/Users/{4}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/4
- Заголовки запроса; -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 4,
  "userName": "User 4",
  "password": "Password4"
}



### 41.GET/api/v1/Users/{414141414141}

- HTTP-метод; **GET**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/414141414141
- Заголовки запроса; -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-daa263794eecff40ba6cdea00d1ac038-c379bf9470a7b84a-00",
  "errors": {
    "id": [
      "The value '414141414141' is not valid."
    ]
  }
}



### 42.PUT/api/v1/Users/{42}

- HTTP-метод; **PUT**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/42
- Заголовки запроса; -H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа; 200
- Тело ответа (при наличии).
{
  "id": 0,
  "userName": "string",
  "password": "string"
}



### 43.PUT/api/v1/Users/{434343434343}

- HTTP-метод; **PUT**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/434343434343
- Заголовки запроса; -H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "
- Тело запроса (при наличии); 
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-46ea49f565afc44bbebd6697933b1e5d-415514ea2e07c24b-00",
  "errors": {
    "id": [
      "The value '434343434343' is not valid."
    ]
  }
}



### 44.DELETE/api/v1/Users/{44}

- HTTP-метод; **DELETE**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/44
- Заголовки запроса; -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 200
- Тело ответа (при наличии).



### 45.DELETE/api/v1/Users/{454545454545}

- HTTP-метод; **DELETE**
- Полный URL запроса;https://fakerestapi.azurewebsites.net//api/v1/Users/454545454545
- Заголовки запроса; -H  "accept: */*"
- Тело запроса (при наличии); 
- Статус-код ответа; 400
- Тело ответа (при наличии).
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-1975fca1246d0b44bde02b80fb6cb7d1-4469c2598aa69642-00",
  "errors": {
    "id": [
      "The value '454545454545' is not valid."
    ]
  }
}
