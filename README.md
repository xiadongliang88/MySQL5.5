# MySQL5.5  

// 启动mysql  
net start mysql  

// 连接数据库  
mysql -hlocalhost -uroot -p

// 显示数据库  
show databases; 

// 创建数据库  
create database test;

// 使用数据库  
use test;

// 显示表  
show tables;

// 创建表  
create table pet (  
name VARCHAR(20),  
owner VARCHAR(20),  
species VARCHAR(20),  
sex CHAR(1),  
birth DATE,  
death DATE);  

