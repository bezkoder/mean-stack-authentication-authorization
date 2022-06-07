# MEAN stack Authentication and Authorization example

Build MEAN stack JWT Authentication & Authorization example with HttpOnly Cookie and JWT.

## Flow for User Registration and User Login
For JWT – Token based Authentication with Rest API, we’re gonna call 2 endpoints:
- POST `api/auth/signup` for User Registration
- POST `api/auth/signin` for User Login
- POST `api/auth/signout` for User Logout

You can take a look at following flow to have an overview of Requests and Responses:

![mean-stack-authentication-authorization-flow](mean-stack-authentication-authorization-flow.png)

For more detail, please visit the tutorial:
> [MEAN stack Authentication & Authorization with Angular 13](https://www.bezkoder.com/mean-stack-auth-angular-13/)

## Run
### Node.js Server
Run `node server.js` for a dev server exporting API at http://localhost:8080/.

### Angular Client
Run `ng serve --port 8081`. Navigate to `http://localhost:8081/`.

## More practice

Fullstack with Node:

> [Angular + Node Express + MySQL example](https://www.bezkoder.com/angular-13-node-js-express-mysql/)

> [Angular + Node Express + PostgreSQL example](https://www.bezkoder.com/angular-13-node-js-express-postgresql/)

> [Angular + Node Express + MongoDB example](https://www.bezkoder.com/mean-stack-crud-example-angular-13/)

> [Angular + Node Express: File upload example](https://www.bezkoder.com/angular-13-node-express-file-upload/)

Serverless with Firebase:
> [Angular Firebase CRUD with Realtime DataBase | AngularFireDatabase](https://www.bezkoder.com/angular-13-firebase-crud/)

> [Angular Firestore CRUD example with AngularFireStore](https://www.bezkoder.com/angular-13-firestore-crud-angularfirestore/)

> [Angular Firebase Storage: File Upload/Display/Delete example](https://www.bezkoder.com/angular-13-firebase-storage/)

Integration (run back-end & front-end on same server/port)
> [How to integrate Angular with Node Restful Services](https://www.bezkoder.com/integrate-angular-12-node-js/)
