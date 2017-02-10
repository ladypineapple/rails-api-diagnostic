# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
// The back end stores data that is accessed by the user indirectly through a server allows developer to control format and flow of information from client.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
// server
```

Which layer in the MVC pattern communicates with the model?

```md
// controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
//because the controller should effect views not the developer
```

What does C.R.U.D stand for?

```md
// create read update destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
// controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
//index show create update destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
//
1.User Action GET is received by the Router
2.Router passes the request on to the appropriate model
3.The model reads the request and finds the appropriate table
4.The model retrieves the result for the second row of the table people
5.This object is passed to the Controller
6.The response is returned to the client.

```

What is the command to generate a new rails-api app?

```bash
// rails new my_api --api
```

What is the command to start an instance of a rails server?

```bash
// bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
//
1.bin/rails db:drop
2.bin/rails db:create
3.bin/rails db:migrate
4.bin/rails db:seed

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
//
```
