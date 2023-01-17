# Introduction-SQL-Datacamp

### Limiting Result
Let's take a look at a few of the genres represented in our library's books.

Recall that limiting results is useful when testing code since result sets can have thousands of results! Queries are often written with a LIMIT of just a few records to test out code before selecting thousands of results from the database.

Let's practice with LIMIT!
Using PostgreSQL, select the genre field from the books table; limit the number of results to 10.

```
-- Select the first 10 genres from books using PostgreSQL
SELECT genre
FROM books
LIMIT 10;
```

![image](https://user-images.githubusercontent.com/117888017/212837597-10869b12-14e7-4a07-b269-547d8a589660.png)
