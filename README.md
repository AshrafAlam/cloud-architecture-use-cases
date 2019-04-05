# Awesome Azure: Use Case Cheat Sheet

While building a scalable system is lot more easier with the advent of cloud technologies, identifying the right fit can be challenging. Usually it may take years of solid experience in architectural space. 

Here we’ve tried to summarize a list of top technologies that can be used to build scalable systems efficiently. 

Few fundamental or basic considerations, such as programming/scripting languages, operating system choices, additional tooling etc have been intentionally ignored to make the list simple.

## Give a Star! :star:

If you like or are using this project to learn or start your solution, please give it a star. 

Have anything to add to the list? Create a PR. 

Thanks!

## Diagram

![Awesome Cloud Architecture](https://raw.githubusercontent.com/EISK/eisk/master/awesome-cloud-architecture.png)

## Table

| Type        | Purpose                              | Use Case                                     | Technology                             
|-------------|--------------------------------------|----------------------------------------------|----------------------------------------
| Client Side | Client Framework                     |                                              | [ReactJS](http://reactjs.org)	                             
| -           | Type System                          |                                              | [TypeScript](https://www.typescriptlang.org)                             
| -           | Design System                        |                                              | [Ant](https://ant.design)                                    
| Backend     | Server Side API Framework            |                                              | [ASP.NET Core Web API](https://docs.microsoft.com/en-us/aspnet/core/web-api)                        
| -           | Concurrency Framework                |                                              | [.NET Task API](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/task-based-asynchronous-programming)                          |
| -           | ORM Framework     					 | Manipulating RDMBS data 						| [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)                     
| -           | Identity Framework  				 | Managing user identity						| [.NET Core Identity](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity)                     
| -           | Cloud Access Framework               | Cloud storage access, logging etc            | [Azure Developer Tools](https://azure.microsoft.com/en-us/tools/)
| -           | Web Socket                           | Sending monthly summary report               | [SignalIR](https://dotnet.microsoft.com/apps/aspnet/real-time)
| Services    | Web Application & API Deployment     | Hosting web applications                     | [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/)
| -			  | Identity Service			         | Managing user identity                       | [Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
| -			  | Telemetry Event Ingestion            | User activity log (receive)                  | [Azure Event Hub](https://azure.microsoft.com/en-us/services/event-hubs/)
| -           | Enterprise Search                    | Product search                               | [Azure Search](https://azure.microsoft.com/en-us/services/search/)
| -           | Prefix-based Search                  | Product search (with prefix)                 | [Azure Search](https://azure.microsoft.com/en-us/services/search/)
| -           | Recommendation                       | Product recommendation                       | [Azure ML](https://azure.microsoft.com/en-us/services/machine-learning-service/)
| -           | Server to Client Notification        | Sending monthly summary report               | [Azure Notification Hub](https://azure.microsoft.com/en-us/services/notification-hubs/)                 
| -           | Report Processing		    		 | Sending monthly summary report               | [Azure Scheduler](https://azure.microsoft.com/en-us/services/scheduler/)                        
| -           | Report Processing                    | Daily operational report                     | [Azure Sql Database with Power BI](https://docs.microsoft.com/en-us/power-bi/service-azure-and-power-bi#azure-sql-database-and-power-bi)
| -           | ALM                                  | Application life cycle management            | [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)                           
| Storage     | Analytics				             | User activity log			                | [Azure CosmosDB: Cassandra as-a-service](https://azure.microsoft.com/en-us/blog/dear-cassandra-developers-welcome-to-azure-cosmosdb/)                             
| -           | Reporting                            | Daily operational report                     | [Azure Sql Database with Power BI](https://docs.microsoft.com/en-us/power-bi/service-azure-and-power-bi#azure-sql-database-and-power-bi)
| -           | Reporting                            | Monthly summary report                     	| [Azure Cassandra as-a-service](https://azure.microsoft.com/en-us/blog/dear-cassandra-developers-welcome-to-azure-cosmosdb/)                             
| -           | Binary content                       | User profile picture, logo                   | [Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/)                     
| -           | CDN Cache                            | User profile picture, logo (cached)          | [Azure CDN](https://azure.microsoft.com/en-us/services/cdn/)
| -           | In Memory Cache                      | User session data                            | [Azure Cache for Redis](https://azure.microsoft.com/en-us/services/cache/)
| -           | Key Value Pair NoSQL Store           | Shopping cart                                | [Azure Table Storage](https://azure.microsoft.com/en-us/services/storage/tables/)
| -           | Document NoSQL Store                 | Product catalog                              | [Azure CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction)
| -           | Graph NoSQL Store                    | Social network graph                         | [Azure CosmosDB: Gremlin API](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction)
| -           | RDBMS 			                     | Financial data - Assets, liabilities, income | [Azure Sql Database](https://azure.microsoft.com/en-us/services/sql-database/)                   
