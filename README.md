# PTSlibrary_2022
This is the documentation of the PTS Library.

It follows an n-tier architecture for the app. We first created the database and added the tables from which we used DAO(Data Access Objects)  for manipulating the data in the database. For the business tier, we used the rest of the classes for activities such as authentication, listing tasks, etc. The facade classes provide ‘templates’ to the business logic classes. So the library mainly houses the business logic. The tier is already created using a Microsoft SQL server.

> The DAO classes are housed in the DAO folder(package).

## Web services
We added web services to the project. We used the SOAP technology for data exchange, which is vital for communication in a Distributed application. As pointed out in the Admin and the Remote components, we faced the same DLL versioning issue. This recurrent issue affected our progress because we were operating in a black hole. We failed to feed information to the database and test the Web services functionality. Another issue in implementing the web services is a recurrent parsing error from their XML config file. We did our best to troubleshoot it, but we remained unsuccessful.
