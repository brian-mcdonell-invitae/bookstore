

 - Create a simple NextJS app to host a book catalog, where users can view the books stored in a postgres database-based catalog
   - simply store title, author and price
   - use nextjs router to expose GET endpoint that simply returns all the books in the table
 - if time permits, create simple reactjs page to view books with drill down to see additional detail on individual book

```

BUILD LOCAL DB:
docker run --name bookstore-db -e POSTGRES_PASSWORD=mypassword -p 5432:5432 -d postgres
    https://dbeaver.io/download/

```
