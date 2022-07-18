# BOOK API

This is a simple API project with Ruby on Rails. With it, it is possible to make three types of requests:

1. GET /api/v1/books (lists all books)
2. GET /api/v1/books/:id (lists a specific book)
3. POST /api/v1/books (uploads a new book).

Body example for POST: 

```
  {
    "name": "testing a book",
    "description": "look aht this book",
    "rating": 5
  }
```
