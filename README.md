
curl --location --request POST 'http://localhost:5000/api/listStudents/' \
--header 'Content-Type: application/json' \
--data-raw '{
    "limit":5,
    "offset":0
} '
curl --location --request POST 'http://localhost:5000/api/addStudent/' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name":"edwin",
    "age":26,
    "class":8
}'
# studentRegistry

Student registry bacnkend file:

