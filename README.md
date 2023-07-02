# Angular-Node-Jwt

This is a sample project to demonstrate Auth operation using Angular with Node, Express, Sequilize and MySql.

## Get started

### Clone the repo

```shell
git clone https://github.com/vikasdevani/angular-node-jwt
cd angular-node-jwt
```

## API Setup

Our API application server is a JSON server application that relies upon some 3rd Party npm packages. You need to install these:

* Install local dependencies (from the project root folder):

    ```
    cd API
    npm install
    ```

  (This will install the dependencies declared in the server/package.json file)
  

* Run migration or Run Node Project:

    ```
    npm start
    ```

* import userinfo.sql file (Optional)




### Client App

Our client application is a straight HTML/Javascript application but our development process uses some npm package.

* Install local dependencies (from the project root folder):

    ```
    cd Frontend
    npm install
    ```

  (This will install the dependencies declared in the package.json file)

Shut it down manually with `Ctrl-C`.


## Running
### Start the Server
* Run the server

    ```
    npm start
    ```
* Browse to the server at [http://localhost:4000]

### Start the Client App
* Run the frontend

    ```
    ng serve --open
    ```
    or
    ```
    npm start
    ```
* Browse to the application at [http://localhost:4200]

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
