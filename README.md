# cs623_project
Code repo for DBMS project (PACE University Spring 23)
Two files with the codes and the images of the outputs have been added to the repo.

This repository contains a Geographic Information System (GIS) database built using MongoDB. 

The database is named "GIS" and includes a collection called "geodata". 

This readme file provides an overview of the database structure and instructions on how to use various functionalities.

1. Create the GIS Database: Open a MongoDB client (such as MongoDB Shell) and create a new database named "GIS"

2. Create the geodata Collection: To create the "geodata" collection within the "GIS" database,

3. Insert locations into the geodata collection, use the insertOne() or insertMany() methods provided by MongoDB
4. To calculate the distance between two points, you can use the $geoNear aggregation pipeline stage in MongoDB. 
5. Find all locations within a certain area, you can use a geospatial query such as $geoWithin 
6. We can use the explain() method to get query execution details, including the query plan, execution time, and index usage.
7. To sort query results in ascending or descending order, you can use the sort() method
8. We can limit the number of results returned using the limit() method.
9. To optimize query performance, consider Indexing techniques
