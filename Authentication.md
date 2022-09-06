# Authentication

<br><br>

## What is OAuth?

<br>

> OAuth is an authorization mechanism to (allow / give permission) other services on your behalf <br>

> It’s an open standard for authorization and anyone can implement it. <br>

> OAuth scenarios almost always represent two unrelated sites or services trying to accomplish something on behalf of users <br>



<br>


## Give an example of what using OAuth would look like.

<br>

> Login into website by gmail for example, were the first website has nothing to do with google

<br>

## How does OAuth work? What are the steps that it takes to authenticate the user?

<br>

> Two services or website dont trust each other, wants to communicate <br>

>  First website connects to the second website on behalf of the user, using OAuth <br>

> The second site asks the user (Should i allow the first website?), user prompted to authorize the first website.

>  The second site generates an authorization token with limited access to the first site   <br>


<br>

## What is OpenID?

<br>

> OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans

<br>


## What is the difference between authorization and authentication?

<br>

> Authentication is validating and verfication process ( prove who you are )   <br>

> Authorization is all about permissions, and what you are allowed to do   <br>


<br>

## What is Authorization Code Flow?

<br>
<br>
<br>
<br>

<img src='https://images.ctfassets.net/cdy7uua7fh8z/2nbNztohyR7uMcZmnUt0VU/2c017d2a2a2cdd80f097554d33ff72dd/auth-sequence-auth-code.png
'>

<br>
<br>
<br>
<br>


## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

<br><br><br><br>

<img src='https://images.ctfassets.net/cdy7uua7fh8z/3pstjSYx3YNSiJQnwKZvm5/33c941faf2e0c434a9ab1f0f3a06e13a/auth-sequence-auth-code-pkce.png'>

<br><br><br>

## What is Implicit Flow with Form Post?

<br><br><br><br>

<img src='https://images.ctfassets.net/cdy7uua7fh8z/6m0uE4E7Hpzbdhyh9dEuYK/e36c910ff47a7540bf27e23c02822624/auth-sequence-implicit-form-post.png'>

<br><br><br>

## What is Client Credentials Flow?

<br>

> machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user.

<br>

## What is Device Authorization Flow?

<br>

> The device asks the user to go to a link on their computer or smartphone and authorize the device. 

<br>

## What is Resource Owner Password Flow?

<br>

> highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials


<br>



