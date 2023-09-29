# Refactoring Java
*_____RentalInfo____
- [x] Restructured class RentalInfo into service folder structure and used this class to have business logic which will generate and return statement with rented movie details, rental amount, loyaltypoints belong to Customer.
- [x] Moved Entities into models folder which gives a better view for peers to identify easily and work.
- [x] used suitable naming conventions for variables and methods.
- [x] Used appropriate data types wherever possible, especially in the constructors of classes.
- [x] Made sure that all fields are private except those needed by other entities or services.
- [x] Added getters/setters as necessary (if any).
- [x] Removed unnecessary code from constructor bodies if it is not required anymore after refactoring.


# Other thoughts and Inprogess implementations
- [x] Current code is a simple refactoring of existing which is provided
- [x] Rewriting this usecase to achieve using SpringBoot, Microservice Architecture, H2 Database and JPA. I will patch that repository in soon.

# Insights of Microservices Architecture approach
- [x] H2 database to manage Data
- [x] Implementation of respective controller, service and repository classes
- [x] Exception Handling
- [x] Dynamic calculation of billing and loyalty points based on Rentals