# PTSlibrary_2022
This is the documentation of the PTS Library.

It follows an n-tier architecture for the app. We first created the database, added the tables from which we  used DAO(Data Access Objects)  for manipulating the data in the database. For the business tier, we used the rest of the classes for activities such as authentication, listing tasks, etc. The facade classes provide ‘templates’ to the business logic classes. So the library mainly houses the business logic. The tier is already created using Microsoft SQL server.

> The DAO classes are housed in the DAO folder(package).

## Web services
We added some web services to this whole project. They we using the SOAP technology for data exachange, which is vitalfor communication in a Distributed aplication. As pointed out in the admin and the remote components, we faced the same DLL versioning issue. This recurrent issue could allow us to proceed further because we were operatiing in a black hole. We hadn't fed any information to the database or even test the Web services. Another issue in implementing the web services is a recurrent parsing error that arose from their XML config file. We did our best to troubleshoot it but we couldn't make it. For the Java part, even though we didn't practically do it, we understood the advantage of heterogentity that distributed applications gives us.
