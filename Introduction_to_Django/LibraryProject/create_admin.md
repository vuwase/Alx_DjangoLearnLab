## Django Admin Setup for Book Model

### Steps Taken:
1. Registered the Book model in `bookshelf/admin.py`.
2. Created `BookAdmin` class with:
   - `list_display` to show title, author, publication_year
   - `list_filter` for author and publication_year
   - `search_fields` for title and author
3. Registered the model with the admin site using `admin.site.register(Book, BookAdmin)`.
4. Accessed admin at `/admin` and verified the configuration.

