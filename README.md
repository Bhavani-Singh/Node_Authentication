# Node_Authentication
Complete authentication app that lets user sign up, sign in, reset password, sign in using social accounts, also maintains log in session upto preset time.

## Features
* Sign Up
* Sign In
* Sign In using social accounts
* Reset passwords

## Tech used:

* NodeJS
* Express
* EJS
* Bootstrap
* Passport-local
* Passport-Google-Oauth
* Mongoose
  
## Folder Structure
```
Node Authentication
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-google.js
    |               |--->passport-local.js
    |
    |                  
    |--->controllers-->|-->user.js
    |                  
    |              
    |--->models---->|-->user.js
    |               
    |
    |--->routes---->|-->index.js
    |
    |              
    |              |--->home.ejs
    |--->views---->|--->reset_password.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
 ````


## Contributing
Contributions are always welcome! If you have any suggestions for improving this application, please feel free to create a pull request or open an issue.
