# RDB-Assessment
## RDB-Assessment
## Tables

### 1. `users` table:

- `user_id`: Unique user identifier
- `email_domain`: Email domain of the user
- `country`: User's country
- `postal`: Postal code
- `mobile_app`: Indicates if the user is using the mobile app
- `sign_up_at`: Date and time when the user signed up

### 2. `progress` table:

- `user_id`: Unique user identifier (linked to the `users` table)
- `learn_cpp`: Progress on learning C++
- `learn_sql`: Progress on learning SQL
- `learn_html`: Progress on learning HTML
- `learn_javascript`: Progress on learning JavaScript
- `learn_java`: Progress on learning Java

## Setup Instructions

1. Download the project files.
2. Use SQLite or DB Browser for SQLite to run SQL commands.
3. Start by exploring the data using basic queries like `SELECT * FROM users` and `SELECT * FROM progress`.

## Tasks

1. **Find the top 25 schools with `.edu` domains.**
2. **Count how many `.edu` learners are in New York.**
3. **Find out how many learners are using the mobile app.**
4. **Use the `strftime()` function to count sign-ups by hour.**
5. **Join the two tables using JOIN and then see what you can dig out of the data!
Do different schools (.edu domains) prefer different courses?
What courses are the New Yorkers students taking?
What courses are the Chicago students taking?**
