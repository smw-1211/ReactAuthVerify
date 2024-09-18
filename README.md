# ReactAuthVerify

Video Referred - https://www.youtube.com/watch?v=T6rElSLldyc&t=2s

A MERN stack project that includes features for email verification, password reset, and email notifications for signup and login. 

## Prerequisites

**Ensure you have the following installed**:

- Node.js (v14 or later recommended)
- npm (Node Package Manager)
- MongoDB (locally or a cloud instance)

#### .env configurations in server folder.

Database = MONGODB_URI

JWTPRIVATEKEY = JWT_TOKEN

SALT = SALT_COUNT

BASE_URL = Set base url.

HOST = Smtp mail host

SERVICE = Service provider - Eg: gmail. 

EMAIL_PORT = EMAIL_PORT_NUMBER

SECURE = true

USER = SENDER_EMAILID

PASS = SENDER_EMAIL_PASSWORD

**Replace the placeholder values with your actual configuration details.**

### Features

> Email Verification: Users receive a verification email upon registration.
> Password Reset: Users can reset their password via email.
> Email Notifications: Users receive email notifications for signup and login activities.

### Troubleshooting

> Port Conflicts: Ensure that ports used by the client and server are not conflicting with other applications.
> Environment Variables: Double-check .env files for accurate configurations.
> Dependencies: If encountering issues, try deleting node_modules and reinstalling dependencies with npm install.

Feel free to adjust the instructions according to the specifics of your setup and any additional configurations or features your project may have.

## Issues

  

Incase you have any difficulties or issues while trying to run the app you can raise it in the issues section.

  

## Pull Requests

  

If you have something to add or new idea to implement, you are welcome to create pull requests on improvement. If you have trained this model on other data and achieved meaningful insights, feel free to create a PR and contribute :smiley:.

  

## Give it a Star
