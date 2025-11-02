
---

### **retrieve.md**
```md
## RETRIEVE OPERATION

### Command used in Django Shell

```python
from bookshelf.models import Book
Book.objects.get(title="1984")
book

<Book: 1984>


