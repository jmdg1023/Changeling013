# Changeling013

```Changeling - A word of play for 'Challenging'```

```013 - Natural number following 012 (The previous challenge in this course)```

## Links to Repo and videoπ

πΈ GitHub Repository [link](https://github.com/jmdg1023/Changeling013)
πΈ Video [link](https://drive.google.com/file/d/1IH92GChwb06MclalcPyifnKLOMdAt57A/view)



## User Story π¨

```http
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

```


## What this project does π‘π‘π‘
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```


## Installation
```npm init

npm install mysql2

npm install sequelize

npm install dotenv
```


## Usage
Run the following command at the root of your project and answer the prompted questions:

```mysql -u root -p```

Enter PW when promted

```source db/schema.sql```

quit

```node seeds index.js```

```npm start```



## Screenshot
![Screenshot](./Screenshot%20GET.jpg)




## Learning Resources π

πΈ[Dotenv](https://www.npmjs.com/package/dotenv)
πΈ[Sequalize](https://www.npmjs.com/package/sequelize)
πΈ[Inquirer](https://www.npmjs.com/package/inquirer)
πΈ[SQL2](https://www.npmjs.com/package/mysql2)




## License π

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/mecuboi/my-profile-website/blob/main/LICENSE)