Q: How would we filter for all books with titles containing the word ‘Django’?
A: You would search through all book objects and find the ones that have Django in the name parameter.

Q: How would we filter for all books with tag ‘Fiction’?
A: Create a list using Book.objects.filter()

Q: How would we filter for all authors who have written books containing the word ‘Django’?
A: Blend of the abovce two options. Create a list of books with Django in the name, and then print each author's name.