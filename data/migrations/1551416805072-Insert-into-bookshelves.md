Query 2: `INSERT INTO bookshelves(name) SELECT DISTINCT bookshelf FROM books;`

- This query will use a simple subquery to retrieve unique bookshelf values from the books table and insert each one into the bookshelves table in the `name` column. This is a great pattern for copying lots of data between tables. 