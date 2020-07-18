# Django REST API Documentation

running on 'http://dev.babylandworld.com/'.

## Open Endpoints

Open endpoints require no Authentication.

- [Login](login.md) : `POST /api/login/`

## Endpoints that require Authentication

Closed endpoints require a valid Token to be included in the header of the
request. A Token can be acquired from the Login view above.

### Current User related

Each endpoint manipulates or displays information related to the User whose
Token is provided with the request:

- [Show info](user/get.md) : `GET /api/user/`
- [Update info](user/put.md) : `PUT /api/user/`

### Account related

Endpoints for viewing and manipulating the Accounts that the Authenticated User
has permissions to access.

<!-- - [Show Accessible Accounts](accounts/get.md) : `GET /api/accounts/`
- [Create Account](accounts/post.md) : `POST /api/accounts/`
- [Show An Account](accounts/pk/get.md) : `GET /api/accounts/:pk/`
- [Update An Account](accounts/pk/put.md) : `PUT /api/accounts/:pk/`
- [Delete An Account](accounts/pk/delete.md) : `DELETE /api/accounts/:pk/` -->
