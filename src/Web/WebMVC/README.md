#Run
Once the deploy process of docker-compose finishes you have to be able to access the services in this urls:
- Web: http://localhost:5100
- Catalog service: http://localhost:5101
- Orders service: http://localhost:5102
- Basket service: http://localhost:5103
- Identity service: http://localhost:5105
- Orders data (SQL Server): Server=tcp:localhost,5432;Database=Microsoft.eShopOnContainers.Services.OrderingDb;User Id=sa;Password=Pass@word;
- Catalog data (SQL Server): Server=tcp:localhost,5434;Database=CatalogDB;User Id=sa;Password=Pass@word
- Identity data (SQL Server): Server=localhost,5433;Database=aspnet-Microsoft.eShopOnContainers;User Id=sa;Password=Pass@word
- Basket data (Redis): listening in localhost:6379






