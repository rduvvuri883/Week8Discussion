# Week8Discussion

•	What are the key differences between block and object storage?

Below are the key differences I gathered based on my reading and understanding on this topic:
1)	Performance
•	Block Storage: - Excels when used for database and OLTP. This can be directly accessed by the OS as a mounted drive.
•	Object Storage: - Best suited for high stream throughput. 
2)	Geography
•	Block Storage: - Latency is directly proportional to the distance between storage and application
•	Object Storage: - Does not have any impact on where the data gets stored
3)	Scalability
•	Block Storage: - Limited scalability
•	Object Storage: - Almost infinite scalability
4)	Analytics
•	Block Storage: - Does not support Analytics as there is no metadata
•	Object Storage: - More suitable for Analytics as the metadata is being captured 
5)	Edit Option
•	Block Storage: - Can be edited as it resides in its own block with a specific address.
•	Object Storage: - Typically, one would not be able to edit a part of the object, but the entire object needs to be edited. 

References: https://www.druva.com/blog/object-storage-versus-block-storage-understanding-technology-differences/

•	What are the key problems do a Data Lake solve?

One of the big alternative Data Lake provides in comparison to Traditional Data Warehouse is allowing unstructured, semi-structured data on top of structured data and the ability to perform Transformation after loading unlike traditional ETL.

It separates compute and storage for the respective teams to scale what is needed.
Data Lake provides the ability to unify data of different formats from disparate data sources and ability for user security based on the data type and roles.

•	Post a screenshot of a lab where you had difficulty with a concept or learned something.

Work in progress

