
```md
## UPDATE OPERATION

### Command used in Django Shell

```python
from bookshelf.models import Book
book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()
book

<Book: Nineteen Eighty-Four>

