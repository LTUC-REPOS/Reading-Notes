# CRUD

<br><br>

## In your own words, describe what each group of status code represents:

<br>

### 100's = informational status codes  <br>
### 200's = success codes## <br>
### 300's = redirection codes  <br>
### 400's = client error codes  <br>
### 500's = server error codes <br>

<br>




<br>

## What is a status code 202?

<br>

> 202 Accepted - Often used for asynchronous processing

<br>


## What is a status code 308?

<br>

> 308  Permanent Redirect

<br>


## What code would you use if an update didn't return data to a client?

<br>

> 204 No Content 


<br>


## What code would you use if a resource used to exist but no longer does?

<br>

> 410 Gone - This is like 404 but we know that the resource existed in the past

<br>


## What is the 'Forbidden' status code?

<br>

> 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

<br>



## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

<br>

> From Server, to make sure its correct <br>
> Into .env, to make it secure

<br>

## What is middleware?

<br>

> Software that lies between the request and response

<br>

## What does app.use(express.json()) do?

<br>

>  To parse the body on server in order to be able to read this information

<br>

## What does the /:id mean in a route?

<br>

> Its called dynamic route in nodejs, it purpose to recieve a parameter "req.params.id"

<br>

## What is the difference between PUT and PATCH?

<br>

>PUT is a method of modifying resource where the client sends data that updates the entire resource <br>
>PATCH applies a partial update to the resource.

<br>

## How do you make a default value in a schema?

<br>

> Using the "default" keyword inside the property of the object

<br>

## What does a 500 error status code mean?

<br>

> Internal server error

<br>

## What is the difference between a status 200 and a status 201?

<br>

> Usually 200 used for fetching, and indicating that everything is OK <br>
> 201 indicates that a request was successful and as a result, a resource has been created



<br>




