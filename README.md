# datatables-sqlserver
I modified ssp class from https://github.com/emran/ssp/blob/master/ssp.php 
It use to generate datatables with server side method on database SQL Server 2008 R2 with PDO_SQLSRV Driver.

Please following instruction below.
1. Make sure PDO_SQLSRV Driver installed on your PHP.
2. Create view on your database and add a column which called 'row' and using function ROW_NUMBER(). See example on file db-example.sql
3. Visit https://datatables.net/examples/server_side/simple.html to follow detail instruction.

Thank you..
