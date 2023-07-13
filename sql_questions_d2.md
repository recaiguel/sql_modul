#Questions

## 1. What is the difference between DELETE and TRUNCATE statements?
DELETE is used to delete one or more tuples of a table. With the help of the "DELETE" command, we can either delete all the rows in
one go or can delete rows one by one. i.e., we can use it as per the requirement or the condition using the Where clause. It is
comparatively slower than the TRUNCATE command. The TRUNCATE command does not remove the structure of the table.

## 2.What is the difference between TRUNCATE and DROP statements?
TRUNCATE is used to delete all the tuples from the table. Like the DROP command, the TRUNCATE command also does not contain a WHERE
clause. The TRUNCATE command is faster than both the DROP and the DELETE command. Like the DROP command we also can’t rollback the
data after using the this command.

is used to remove table definition and indexes, data, constraints, triggers etc for that table. Performance-wise the DROP command is
quick to perform but slower than TRUNCATE because it gives rise to complications. Unlike DELETE we can’t rollback the data after
using the DROP command. In the DROP command, table space is freed from memory because it permanently delete table as well as all its
contents.