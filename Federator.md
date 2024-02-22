![1.3.1 Federator](TeamOneFiles/Federator%20Diagram.svg)

| Name | 1.3.1 Federator |
| ----------- | ----------- |
| Purpose | Displays the internal components of the Federator and how it communicates information to other parts of the program.  |
| Description | The federator receives queries from Logic on specific information needed and decides where to send the query. It requests information from the external and scheduling databases, formats it, and returns it to Logic. It also receives schedules from Logic and stores those in the Scheduling Database. |
| Requirements | Requirements 3, 6, 8, 14, 16 |
| Elements | 1.3.1.1 Query Manager. Processes the requests from Logic. Determines if the request should be sent to the External or Scheduling Database. |
|          | 1.3.1.2 Data Processor. Receives the data from the External and Scheduling Databases, packages it, and returns it to Logic. |
|          | 1.3.2 External Database. Retrieves and stores information from external sources. |
|          | 1.3.3 Scheduling Database. Stores scheduling information for users. |
| Referenced by | 1.3 Storage, 1.2 Logic Component |
| Viewpoint | UML Component Diagram |