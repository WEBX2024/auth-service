# auth-service
This is a partially working authentication service.

required dependencies:
1. bcryptjs
2. cors
3. dotenv
4. express
5. jwt
6. mongoose
7. morgan
8. nodemailer
9. otp-generator

Status:
Till now you can sign-up,login, otp verification by this projectYet it's not fully completed few developments are ongoing e.g. Data fetch in profile page and forgot password is not in working condition but after completing this project, can be a well mannered and scalable authenticator system. 

Usage procedure:
1. Clone the repo
2. Install dependencies-->npm install
3. Create .env file and add the environment variables
    a. Port
    b. Mongodb_url
    c. Email_user
    d. Email_pass
    e. Otp_expiry
4. To start the service --> npm start