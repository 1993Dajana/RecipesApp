# RecipesApp
-------------
1.Import database Recipes in Microsoft SQL Management Studio under localhost\SQLEXPRESS <br>
----------
2.Merge Recipes database with existing ASPNETDB.MDF database in App_Data <br>
---------
* Navigate to: C:\Windows\Microsoft.NET\Framework\v4.0.3**** <br>
* Find file: aspnet_regsql and run it (choose Recipes databaase in one of the wizard steps) <br>

3.Change connectionString in web.config if Data source is different than localhost <br>
--
``` 
connectionString="Data Source=LOCALHOST\SQLEXPRESS ; Initial Catalog = Recipes ; Integrated Security = True;"

```
 
