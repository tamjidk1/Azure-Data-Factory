# Azure-Data-Factory
Azure Data Factory

Problem Statement:
XYZ Company has requested to get a file that lists of all the products the company sells (source). They also requested the model description which is a different table (source & transform – we will use lookup & select). The shipping weight needs to be calculated by padding the actual weight plus 10% to account for packing (transformation – we will use calculation & derive column). Finally, we will load the data to Azure SQL by list price descending (sort and sink)

Introduction:
Azure Data Factory (ADF) will extract text files from azure storage, transform it in ADF and load it to azure SQL Database.

Getting Started:
For this project to work, we need
a) Azure blob storage
b) Azure Data Factory
c) Azure SQL

I have added Steps by Steps pdf files about how to create dataflows and pipelines with sources and destination.
