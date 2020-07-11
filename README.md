# Oracle_Sample_Schema - OT

Introduction to the OT Oracle sample database
We provide you with an Oracle sample database named OT which is based on a global fictitious company that sells computer hardware including storage, motherboard, RAM, video card, and CPU.

The company maintains the product information such as name, description standard cost, list price, and product line. It also tracks the inventory information for all products including warehouses where products are available. Because the company operates globally, it has warehouses in various locations around the world.

The company records all customer information including name, address, and website. Each customer has at least one contact person with detailed information including name, email, and phone. The company also places a credit limit on each customer to limit the amount that customer can owe.

Whenever a customer issues a purchase order, a sales order is created in the database with the pending status. When the company ships the order, the order status becomes shipped. In case the customer cancels an order, the order status becomes canceled.

In addition to the sales information, the employee data is recorded with some basic information such as name, email, phone, job title, manager, and hire date.

Oracle sample database diagram
The following illustrates the sample database diagram:

Oracle Sample Database
Table Names	Description	Records
 CONTACTS	store contact person information of customers	319 records
 COUNTRIES	store country information	25 records
 CUSTOMERS	store customer master	319 records
 EMPLOYEES	store employee master	107 records
 INVENTORIES	store inventory information of products	1112 records
 LOCATIONS	store locations of warehouses	23 records
 ORDERS	store order header information	105 records
 ORDER_ITEMS	store order line items	665 records
 PRODUCT_CATEGORIES	store product categories	5 records
 PRODUCTS	store product information	288 records
 REGIONS	store regions where the company operates	4 records
 WAREHOUSES	store warehouse information	9 records
 
 Oracle native JSON:

https://oracle-base.com/articles/12c/json-support-in-oracle-database-12cr1#introduction-to-json


Materialized View:

https://oracle-base.com/articles/misc/materialized-views


List Agg:

https://oracle-base.com/articles/12c/listagg-function-enhancements-12cr2


REST:

https://dzone.com/articles/oracle-rest-data-services-on-autonomous-transactio

https://oracle-base.com/articles/misc/oracle-rest-data-services-ords-create-basic-rest-web-services-using-plsql

https://panoplytechen.wordpress.com/2019/09/01/first-steps-with-oracle-rest-data-services-on-windows/

XML:

https://oracle-base.com/articles/misc/sqlxml-sqlx-generating-xml-content-using-sql

APEX:

https://oracle-base.com/articles/misc/oracle-application-express-apex-installation

QUEUE:

https://oracle-base.com/articles/9i/advanced-queuing-9i

Scheduler Job:

https://oracle-base.com/articles/10g/scheduler-10g

Oracle Cloud:
Compute Instance: https://docs.cloud.oracle.com/en-us/iaas/Content/Compute/Tasks/managingkeypairs.htm

Create Autonomous Database: https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/tutorial-getting-started-autonomous-db/index.html

SQL Developer Web: https://docs.oracle.com/en/cloud/paas/atp-cloud/atpug/sql-developer-web.html#GUID-102845D9-6855-4944-8937-5C688939610F

APEX: https://www.youtube.com/watch?v=VlYa5xkF_kE


