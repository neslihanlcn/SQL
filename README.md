# SQL Odev3
select * from Suppliers
where Country LIKE 'A%a';

select * from Suppliers
where Country  LIKE '______%y';

select * from Suppliers
where ContactTitle LIKE '%a%a%a%';

select ContactTitle,SupplierID,Phone from Suppliers
where ContactTitle LIKE 'C%' and SupplierID > 10 and Phone LIKE '(0%';
