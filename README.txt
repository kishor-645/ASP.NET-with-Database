Step-1   Deploy your Application
Step-2   Create One Database and run the below query

create table student(student_id varchar(50),student_name varchar(50),course varchar(50),address varchar(50),email varchar(50),phone varchar(50))

Step-3 Mention your Database Details into below files Than your application can coordinate with database  
1. record.aspx.cs
2. StudentRegistration.aspx.cs

Modify this line in both file::      

SqlConnection con = new SqlConnection(@"Data Source=this-is-dbserver02.database.windows.net,1433;Initial Catalog=Db02;User ID=kishor;Password=Potato@95Grams");



Step-4  Add this below file name as default page 

StudentRegistration.aspx

After that you can access your webapp
Done::::

