# anki_vscode::mysql

## 这里是问题：什么是markdown

<!-- notecardId: 1725724859274 -->

这里是问题描述，问题描述后请另起一行加一个`%`符号，如下

%

这里是答案：markdown是一种 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。

## Combine Two Tables

<!-- notecardId: 1725725190990 -->

Table: Person

+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| personId    | int     |
| lastName    | varchar |
| firstName   | varchar |
+-------------+---------+

personId is the primary key (column with unique values) for this table.
This table contains information about the ID of some persons and their first and last names.`%`

%

addressId is the primary key (column with unique values) for this table.
Each row of this table contains information about the city and state of one person with ID = PersonId.
 

Write a solution to report the first name, last name, city, and state of each person in the Person table. If the address of a personId is not present in the Address table, report null instead.

Return the result table in any order.

The result format is in the following example.

+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| addressId   | int     |
| personId    | int     |
| city        | varchar |
| state       | varchar |
+-------------+---------+