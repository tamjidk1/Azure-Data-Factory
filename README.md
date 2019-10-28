# Azure-Data-Factory
Azure Data Factory

Problem Statement:
XYZ Company has requested to get a file that lists all the products the company sells (source). They also requested the model description which is in a different table (source & transform – we will use lookup & select). XYZ company shipping weight needs to be calculated by padding the actual weight plus 10% to account for packing (transformation – we will use calculation & derive column). Finally, they want to load the data to Azure SQL by list price descending (sort and sink)

Introduction:
To solve this, we need to use Azure Data Factory (ADF) that will extract text files from azure storage, transform it in ADF and load it to azure SQL Database.

Getting Started:
For this project to work, we need
a) Azure blob storage
b) Azure Data Factory
c) Azure SQL

I added Steps By Steps ADF Process pdf file about how to create dataflow and pipeline with sources and destinations.
