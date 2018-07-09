#12: Supplementary topic

This is a supplementary topic that addressess refactoring the MyRent suite to make it compatible with databases, such as Mongo, where the model id (the primary key) is auto-generated in the service. To date the id has been generated in the client and passed to the service (Play). It also provides a pattern applicable where the Retrofit Callback<T> is required with more than one type of response body T.


