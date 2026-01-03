SET autocommit = 0;
CREATE TABLE orders (
    order_id INT PRIMARY KEY,
    customer_name VARCHAR(50),
    product VARCHAR(50),
    quantity INT,
    order_date DATE
);

start transaction;
savepoint A;
INSERT INTO ORDERS value (1,'Dinesh','Mobile',1,curdate());
savepoint B;
INSERT INTO ORDERS value (2,'Ramesh','Laptop',2,curdate()+10);
savepoint C;
INSERT INTO ORDERS value (3,'Mahesh','Buds',10,curdate()-100);
savepoint D;
INSERT INTO ORDERS value (4,'Malaya','Cover',4,curdate()-210);
savepoint E;
rollback to B;

select * from orders;
commit;
