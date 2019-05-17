# Homework
INSERT INTO nama_table (field1,field2,...) VALUES ('data1','data2',...)
UPDATE name_table SET field1=new_value, field2=new_value, ... WHERE condition1,condition2, ...
select count * from person
update person set mobile = null where id={6}
select max(id) from person
select min(id) from person
select avg(id) from person
select sum(id) from person
select concat (first_name , ' ' , last_name) from person
select replace (first_name ,'س','ص',) from person
select * from person whre id between 3 and 7
select * from person order by national_code
select * from person order by national_code desc
select * from person where First_Name lik '%1%'
select top3 * from person order by id desc
select top3 * from person
select count *,mobile from person group by mobile
select max(id), city from person group by city
select count(id),city from person group by city having count(id) > 2
