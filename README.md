# SpringBootwMongoJMS

created this simple Spring Boot Application which does-
    1. CRUD operations on Employee (id and name)
    2. Exposes REST based apis for GET, POST and DELETE
    3. Sends employee information to ActiveMQ queue for asynchronous processing.
    4. Listener processor to process the request
    5. Uses MongoDB to store Employee information (table=Employee)
    6. Uses MongoDB to track progress of asynchronous processing. (table=Tracker)
    7. Uses Logging
