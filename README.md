# Identity-sample
Asp .net Core 2.0, C#


Asp .net Core 2.0
### Create Database using Sql Server 

```Database name - "YourDatabaseName"```

### Change Coonection String According Your Sql Server
### change appsettings.json'

```
"ConnectionStrings": {
    "DefaultConnection": "Data Source=Sql servername;Initial Catalog=YourDatabaseName;Integrated Security=True"
  },
```
### Add migreation cmd using package manager console (go UnitOfWorkWithRepositoryPartens.Data using package manager console)

```Add-Migration InitialCreate```
```Update-Database```

### Run Application 
