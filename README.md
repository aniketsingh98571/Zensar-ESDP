# Zensar-ESDP
Following are the software's required to download. 
 
- MySQL
- MYSQL workbench
- Oracle 11g
- SQL Developer 19.2.1

These are the links to download
1. [MYSQL 5.x command line client (latest version will also do)](https://dev.mysql.com/downloads/windows/installer/5.5.html)
2. [MYSQL Workbench 5.x  (latest version will also do) ](https://dev.mysql.com/downloads/workbench/5.2.html) (download and install installer) 
3. [SQL Developer 19.2.1](https://www.oracle.com/in/tools/downloads/sqldev-v192-downloads.html)
4. [Oracle 11g express edition (Download according to 32bit or 64 bit)](http://www.oracle.com/technetwork/database/database-technologies/express-edition/downloads/index.html)

Note: If it is asking for username and password, you can sign up on oracle and use the same and then download.

### In this sessions we have used HR schema which is a predefined schema provided by Oracle. So after installation of sql dev tool and Oracle 11 g 
Do follow this steps.
1. Open cmd
2. `sqlplus`
3. Type username as `system` and for password you have to use that password which you have given on sign up.
5. CONNECT system/admin
6. ALTER USER hr IDENTIFIED BY hr ACCOUNT UNLOCK;
7. CONNECT hr/hr;
8. SELECT * FROM departments;
