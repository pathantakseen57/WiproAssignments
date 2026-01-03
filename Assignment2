create database customerdb;
use customerdb;

CREATE TABLE customers (
    customer_id INT PRIMARY KEY,
    customer_name VARCHAR(50),
    email VARCHAR(50),
    city VARCHAR(30),
    phone VARCHAR(15),
    created_date DATE
);

INSERT INTO customers VALUES
(1, 'Amit Sharma',  'amit@gmail.com',   'Delhi',    '9876543210', '2023-01-10'),
(2, 'Sneha Patel',  'sneha@gmail.com',  'Mumbai',  '9876543211', '2023-02-15'),
(3, 'Rahul Verma',  'rahul@gmail.com',  'Delhi',   '9876543212', '2023-03-20'),
(4, 'Neha Singh',   'neha@gmail.com',   'Bangalore','9876543213','2023-04-05'),
(5, 'Ankit Kumar',  'ankit@gmail.com',  'Delhi',   '9876543214', '2023-05-12');


select * from customers;

SELECT customer_name, email
FROM customers
WHERE city = 'Delhi';
