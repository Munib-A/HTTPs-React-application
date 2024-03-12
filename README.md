# HTTPs-React-application
## Generate certificates
- openssl req -nodes -new -x509 -keyout server.key -out server.cert

## To Run Without NPM
- ```npx create-react-app my-react-app ```
- ```npm start ```

## To Run With NPM
- add server.js to your project's root directory, add the certificates, a build directory and run the following command:
``` npm run build ```
- Wait for this to complete. Once done, run:
``` npm start ```

- You may clone the project for reference.
