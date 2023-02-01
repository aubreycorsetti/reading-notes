# Day 27 Notes

## Authentication & Production Server

### JSON Web Tokens

• A JSON Web Token (JWT) is a compact and self-contained way for securely transmitting information between parties as a JSON object.

• It is often used for authentication and authorization purposes. (it can be signed and verified using a secret key).

• JWTs typically consist of a header, a payload, and a signature, and are often used in web and mobile applications.

• You shoulw use JSON Web Tokens for authorization and information exchange

• JSON web tokens consist of 3 parts, separated by dots which are: Header, Payload and Signature. EX: xxxxx.yyyyy.zzzzz

• Header: The header typically consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA.

• Payload: Contains the claims. Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims.

  > Registered claims: set of predefined claims that are recommended

  > Public claims: can be defined at will by those using JWTs.

  > Private claims: custom claims created to share info between parties that agree on using them and are neither registered or public claims.

• Signature: To create the signature part you have to take the encoded header, the encoded payload, a secret, the algorithm specified in the header, and sign that. The signature is used to verify the message wasn't changed along the way, and, in the case of tokens signed with a private key, it can also verify that the sender of the JWT is who it says it is.

### DRF JWT Authentication

• The JWT is acquired by exchanging an username + password for an access token and an refresh token.

• The access token is usually short-lived (expires in 5 min or so, can be customized though).

• The refresh token lives a little bit longer (expires in 24 hours, also customizable). It is comparable to an authentication session. After it expires, you need a full login with username + password again.

• First step is to authenticate and obtain the token. The endpoint is /api/token/ and it only accepts POST requests.

• To get a new access token, you should use the refresh token endpoint /api/token/refresh/ posting the refresh token:

### Django Runserver Is Not Your Production Server

• If you want to run Django in production, be sure to use a production-ready web server like Nginx, and let your app be handled by a WSGI application server like Gunicorn.

• If you plan on running on Heroku, a web server is provided implicitly. You don’t have to take care of it. You just need to specify a command to run your application server (again, Gunicorn is fine) in the Procfile.

#### Things I want to know more about

> how to implement and run my app using JWTs

#### Sources

[JSON Web Tokens](https://jwt.io/introduction/)
[DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
[Django Runserver Is Not Your Production Server](https://vsupalov.com/django-runserver-in-production/)

Click to return [Home!](../README.md)
