# Weekend Four Solution
Code as presented during the walkthrough in class.

## Get Started
1. Run `npm install`

2. Create omicron database in postico

3. Navigate to the postico omicron database

4. Click `SQL Query` in postico

5. Paste the following statement from database.sql

  ```
    CREATE TABLE tasks (
      id SERIAL PRIMARY KEY,
      task_content varchar(255) NOT NULL,
      created_date date DEFAULT NOW(),
      completed_date date DEFAULT NULL
     );
  ```
6. Run `npm test` to start nodemon or `npm start` to run node

7. Navigate to `localhost:3000`
