# Simple Node.js program to insert (csv) file/s into mysql database

## Installation 
You need to run `npm install`

## How to use it
- Put any csv file/s in the `files` folder, then run the app.js in node.
- Make sure your csv file/s are valid; each column should be sperated by comma `,`
- The number of the columns in the rows after the first rows should match with the number of column in the first row, otherwise you will get an Error.
- Change the password in the `connection` varible in the `app.js` file to your password, and the database name to your database name.
