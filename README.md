
# Bamazon
Bamazon is a CRM that focuses on sales. It provides command-line interfaces for customers, managers, and supervisors.


## How to Run
To run Bamazon on Windows and Mac, you will need [Bash](https://git-scm.com/downloads/), [Node](https://nodejs.org/en/), [npm](https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm), and [MySQL Workbench](https://dev.mysql.com/downloads/workbench/).


1. In Bash, type `git clone https://github.com/DanBrit/Bamazon` to download Bamazon.

2. Navigate to the directory then type `npm install` to download the required packages.

3. In MySQL Workbench, connect to `localhost:3306` and run `bamazon_schema.sql` then `bamazon_seeds.sql`.

4. Finally, in Bash, type `node bamazonCustomer.js` to log in as a customer and `node bamazonManager.js` to log in as a manager.

