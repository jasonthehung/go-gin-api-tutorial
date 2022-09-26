We can use:

curl localhost:8080/books to call our getBooks function

curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"

in zsh, using curl localhost:8080/checkout?id=2 --request "PATCH" will failed.

curl -s -X PATCH 'localhost:8080/checkout?id=2'
