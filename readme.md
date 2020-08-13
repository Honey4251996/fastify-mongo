# Fastify REST API Framework

> $ mongod

> $ node index

## Testing the API endpoints

- Adds a new user
"""
localhost:3000/api/users -X POST --data {
    "name": "chidume",
    "age": 27,
    "email": "kurtwanger5@gmail.com"
}
"""
- Returns all users
"""
localhost:3000/api/users -X GET
"""
- Get specific users
"""
localhost:3000/api/users/5f34a7ab5c67553e584afcc7 -X GET
"""
- Edit user "5f34a7ab5c67553e584afcc7"
"""
localhost:3000/api/users/5f34a7ab5c67553e584afcc7 -X PUT {
    "name": "first user",
    "age": 27,
    "email": "kurtwanger5@gmail.com"
}
"""
- Delete user "5f34a7ab5c67553e584afcc7"
"""
localhost:3000/api/users/5f34a7ab5c67553e584afcc7 -X DELETE
"""

[Reference URL](https://blog.bitsrc.io/how-to-build-rest-apis-with-fastify-2eac64536a72)
