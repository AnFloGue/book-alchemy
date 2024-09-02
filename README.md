# Book Alchemy API endpoints



## Running the application
```bash
python -m flask run
```

### Home Page
- URL: /
- Method: GET
- Description: Displays a list of all books.


### Add Author Page
- URL: /add_author
- Method: GET, POST
- Description: Displays a form to add a new author and handles form submission.

### Add Book Page
- URL: /add_book
- Method: GET, POST
- Description: Displays a form to add a new book and handles form submission.

### Delete Book Page
- URL: /book/<int:book_id>/delete
- Method: POST
- Description: Deletes a book by its ID.

### Search Book
- URL: /?search=\<search_query\>
