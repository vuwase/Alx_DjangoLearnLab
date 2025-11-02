

```md
## DELETE OPERATION

### Command used in Django Shell

```python
from bookshelf.models import Book
book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()
Book.objects.all()

(1, {'bookshelf.Book': 1})
<QuerySet []>

