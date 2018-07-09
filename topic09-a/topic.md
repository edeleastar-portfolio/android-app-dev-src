#9-a: Client-Service

To date we have developed MyRent as a standalone application in which its data is stored in a SQLite database. In this topic we split the app into client-server modules. SQLite is retained but functions as a local cache, the primary model data repository now being allocated to a service. In developing the service we adopt a test-driven-development (TDD) approach, using a simple Play JUnit app to verify the service before refactoring the standalone MyRent app into a client capable of consuming the service api.
