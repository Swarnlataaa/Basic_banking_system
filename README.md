# Basic_banking_system
- Clone the repository in Htdocs of XAMPP.
- open localhost/folder_name(you cloned in inside xampp)
- set up php_my_Admin
- [Preview](https://youtu.be/zPiphZ3H_i0)
```
CREATE TABLE customers (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(255),
    Amount INT
);

CREATE TABLE transaction (
    ID INT AUTO_INCREMENT PRIMARY KEY,
    `From` VARCHAR(255),
    `To` VARCHAR(255),
    Amount INT
);

```

-
```
-- Insert data into the "customers" table
INSERT INTO customers (Name, Amount) VALUES
    ('Alice', 1000),
    ('Bob', 1500),
    ('Charlie', 800),
    ('David', 2000);

-- Insert data into the "transaction" table
INSERT INTO transaction (`From`, `To`, Amount) VALUES
    ('Alice', 'Bob', 500),
    ('Charlie', 'David', 300),
    ('Bob', 'Charlie', 200),
    ('David', 'Alice', 700);

```
