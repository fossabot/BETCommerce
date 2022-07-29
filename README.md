# BET E-Commerce App
A simple E-Commerce application demonstrating .NET Capabilities with Clean code architecture
# ![WebApp](https://github.com/swagfin/BETCommerce/blob/da22d78db5caf6917bf8a37c4dc90b073a2c8e6b/BetCommerce.WebClient/Screenshots/shop.png)

### Deploying to Docker Containers

  This repository has a workflow run that publishes to Docker Hub supporting windows and Linux Container;
  - [Go to Docker Hub - API](https://hub.docker.com/r/swagfin/betcommerceapi).
  - [Go to Docker Hub - Web Client](https://hub.docker.com/r/swagfin/betcommercewebclient).
  
 You can use the following CLI commands to pull the Docker Containers:

```powershell
# Pull Image 'BET E-Commerce API':
docker pull swagfin/betcommerceapi

# Pull Image 'BET E-Commerce Web Client':
docker pull swagfin/betcommercewebclient

```
 
 ### Local Environment Setup
-  Open project BETCommerce/BETCommerce.sln
-  *Database* 
   -  The Entity Framework will Automatically generate a database migration for you (save the hussle)
-  *Web Api & Server Application*
   -  Right click solution and set startup projects to BetCommerce.API and BetCommerce.WebClient
   -  Build and Run Project through Visual Studio/Terminal
   -  To Access API - https://localhost:5001/swagger/index.html
   -  To Access WebClient - https://localhost:6001/
   -  There may be demo data products and categories to interact with
   
### Bugs / Feature Request
This application is still under development and may not be production ready but if you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/swagfin/BETCommerce/issues/new) by including your search query and the expected result.
If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/swagfin/BETCommerce/issues/new). Please include sample queries and their corresponding results.

## To-do
There is some few features in Milestone;
- Admin/Superuser Portal for performing crud operations.
- Completing Multi-Timezone Support.

# Lisence
This project's license is in review.
# Contact
George Wainaina georgewainaina18@gmail.com
