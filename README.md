# Getting Started

### Sending request

For authentication via auth-server:
* You should run [auth-server](https://github.com/kuzminal/Spring-Security-Auth-Server)
* Then you will be able to login by GET http://localhost:9090/login with the following headers:
    - username: danielle 
  - password: 12345
    
* You can find in database table OTP the code for your request
* Put that code into next login request instead of password:
    - username: danielle
    - code: {your otp code from database}
    
* You are logged in now!