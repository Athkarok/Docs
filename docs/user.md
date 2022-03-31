# User

![user_model](./img/user.png)

| ATTRIBUTE | DATATYPE | DEFINITION |
| --- | --- | --- |
| id | INT | PK |
| email | STRING | An Email is the email that we use to communicate with the user and authentication. An Email is UNIQUE, REQUIRED. |
| username | STRING | A Username is UNIQUE, REQUIRED. |
| password | STRING | A Password is the secret keyword of the user. A Password is used for user authentication. A Password is NOT UNIQUE, REQUIRED. |
| first\_name | STRING | First name of the owner of the account. useful for interaction with the user via emails.  NOT UNIQUE, REQUIRED. |
| last\_name | STRING | Last name of the owner of the account. useful for interaction with the user via emails.  NOT UNIQUE, REQUIRED. |
| phone\_number | STRING | A Phone\_number is the phone number the user used for communication with the user. A Phone\_number is UNIQUE, NOT REQUIRED. |
| points | INT | Points are the number of points the user got while using the app. Points are NOT UNIQUE, REQUIRED, CHANGING.|
| role | STRING | A Role indicate the permission the user has, and what resources to access. A Role are NOT UNIQUE, REQUIRED, CHANGING.|
