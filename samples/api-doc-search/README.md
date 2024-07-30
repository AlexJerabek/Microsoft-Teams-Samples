
## This sample is having two solutions
Setup the CosmosDB and Azure Function solution (`azure-function-nodejs`) firstly to create and store embedding vectors in CosmosDB and then setup, run the API application (`nodejs`) to perform RAG-based semantic search using Azure CosmosDB NoSQL with embedding vector-based search for user queries.

## azure-function-nodejs
This Azure function will be triggered to create and store embedding vectors in CosmosDB once a file is uploaded to Azure Blob Storage or local storage emulation.

## nodejs
This sample API application demonstrates how to perform RAG-based semantic search using Azure CosmosDB NoSQL with embedding vector-based search for user queries.