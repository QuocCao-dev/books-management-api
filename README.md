### API
#### Tags:
- [x] `GET` `http://localhost:4200/api/books`: get all tags
- [x] `POST` `http://localhost:4200/api/books`: create new tag
```json
{
    "name": "Javascript"
}
```
```json
{
    "name": "Javascript"
}
```
#### Books
- [x] `GET` `http://localhost:4200/api/books`: get all books
- [x] `GET` `http://localhost:4200/api/books/:id`: get book by id
- [x] `POST` `http://localhost:4200/api/books/:id`: create new book
```json
{
    "name": "Learn Reactjs in 30 days",
    "description": "learn react in 30 days",
    "price": 1200,
    "publicationDate": "2023",
    "author": "Cao Anh Quoc",
    "tags": ["8a70c12d-3e26-4949-af1b-a2cd66a36455"] // optional
}
``` 
- [x] `PATCH` `http://localhost:4200/api/books/:id`: update book
```json
{
    "name": "Learn Reactjs in 30 days",
    "description": "learn react in 30 days",
    "price": 1200,
    "publicationDate": "2023",
    "author": "Cao Anh Quoc",
    "tags": ["8a70c12d-3e26-4949-af1b-a2cd66a36455"] // optional
}
```
- [x] `DELETE` `http://localhost:4200/api/books/:id`: delete book