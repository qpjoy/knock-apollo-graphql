### graphiql
```
mutation {
  postBook(title: "Harry Potter and the Chamber of Secrets", price: 250, author: "JK Rowling") {
    _id
    title
    price
    author
  }
}

# query {
#   getAllBooks {
#     _id
#     title
#     price
#     author
#   }
# }
```