### node.js-practice-2-mongodb

#### GET http://localhost:8000/contacts  

#### POST http://localhost:8000/contacts
{  
  "name": "Sun Sun",  
  "number": "000-12-34"  
}  

#### DELETE http://localhost:8000/contacts/:contactId

#### GET http://localhost:8000/contacts/:contactId

#### PUT http://localhost:8000/contacts/:contactId
{  
    "name": "Jacob Mercer POST",  
    "number": "761-23-96-888"  
}  

#### PATCH http://localhost:8000/contacts/:contactId/contactName
{  
    "name": "Jacob Mercer PATCH"  
}  