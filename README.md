# EntityFrameworkCoreDatabaseFirst
TOOLS - How to use EntityFrameworkCore Database First

```
install-package Microsoft.EntityFrameworkCore
install-package Microsoft.EntityFrameworkCore.Relational
install-package automapper
install-package FluentValidation
install-package Microsoft.Extensions.Configuration.FileExtensions
install-package Microsoft.Extensions.Configuration.Json
install-package Microsoft.EntityFrameworkCore.SqlServer
```


```
dotnet tool install --global EntityFrameworkCore.Generator
efg initialize -c "server=SERVER;database=DB;User ID=Username;password=xxxxxx;"
efg generate -c "server=SERVER;database=DB;User ID=Username;password=xxxxxx;" --validator --mapper --models
```
