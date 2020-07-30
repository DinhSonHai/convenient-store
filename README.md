Online Convenient Store Website using C#, ASP.NET, Entity Framework, SQL Server <br/>
1 Open SQL Server 2008 or above, save your server name, open file ConvenientStore.sql, select all text and click execute to create Database
![Server name](https://github.com/DinhSonHai/bookstore-manager/blob/master/installation-image/serverName.png)
<br/><br/>
2 Open Visual Studio 2017 or above <br/>
2.1. Open App.config, replace selected part with your server name <br/><br/>
![Connect to Database](https://github.com/DinhSonHai/convenient-store/blob/master/ConvenientStore/Data/images/appConfig.png)
<br/><br/>
2.2. Open web.config, replace selected part with your server name <br/><br/>
![Connect for Report Feature](https://github.com/DinhSonHai/convenient-store/blob/master/ConvenientStore/Data/images/webConfig.png)
<br/><br/>
Sample Account to login to application:
* administrator: admin - Password123
* employee: trana - Password123
* client: sonhai - Password123<br/>
If you login as administrator, website will redirect to Admin page and you can use full feature<br/>
If you login as employee, website will redirect to Admin page and you can use basic feature, except employee manager and account manager<br/>
If you login as client, website will redirect to home page and you can buy your favorite product<br/>
