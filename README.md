# react-auth-boilerplate

* Uses: 
	* access tokens
	* refresh tokens
	
* Technologies: 
	* Typescript 
	* GraphQL
	* Type-GraphQL 
	* TypeORM
	* PostgreSQL
	* React with hooks
	* Apollo
	
* Backend features: 
	* GraphQL server using TypeGraphQL and TypeORM 
	* Register users (email, password)
	* Login and creates access and refresh tokens
	* Authenticated mutations/quiers
	* Revoke tokens for users

* Frontend features (barebones): 
	* Uses Apollo and GraphQL Code Generator
	* React Router 
	* Register/Login
	* Persists session on refresh
	* Handles expired tokens
	* Fetches current user in header 

## Install 
```bash
git clone github.com/derekacosta/react-auth-boilerplate

yarn install
```
	
## Make sure to setup PostgreSQL for the GraphQL server

1. Install PostgreSQL on your computer
2. Create database (default is called jwt-auth)