# Join
Simple Intro: http://www.w3school.com.cn/sql/sql_join.asp
## Inner Join
即JOIN: 如果表中有至少一个匹配，则返回行
### 语法
```sql
SELECT column_name(s)
FROM table_name1
INNER JOIN table_name2 
ON table_name1.column_name=table_name2.column_name
```
See: http://www.w3school.com.cn/sql/sql_join_inner.asp
## Left Join
LEFT JOIN 关键字会从左表 (table_name1) 那里返回所有的行，即使在右表 (table_name2) 中没有匹配的行。
### 语法
```sql
SELECT column_name(s)
FROM table_name1
LEFT JOIN table_name2 
ON table_name1.column_name=table_name2.column_name
```
See: http://www.w3school.com.cn/sql/sql_join_left.asp

## Right Join
RIGHT JOIN 关键字会右表 (table_name2) 那里返回所有的行，即使在左表 (table_name1) 中没有匹配的行。
### 语法
```sql
SELECT column_name(s)
FROM table_name1
RIGHT JOIN table_name2 
ON table_name1.column_name=table_name2.column_name
```
See: http://www.w3school.com.cn/sql/sql_join_right.asp
## Full Join
只要其中某个表存在匹配，FULL JOIN 关键字就会返回行。
### 语法
```sql
SELECT column_name(s)
FROM table_name1
FULL JOIN table_name2 
ON table_name1.column_name=table_name2.column_name
```
See: http://www.w3school.com.cn/sql/sql_join_full.asp
