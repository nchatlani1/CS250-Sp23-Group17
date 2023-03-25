# CS250-Sp23-Group17

Nitin Chatlani
Brandon Ho
Sumeya Sayd

Software Design Specification
CarRentalStore: Class that would include the location of the store the customer would rent the vehicle from and the cars available to be rented at the specific location. 
Attributes:
Location: a String variable that contains the name of the location of the Rental Store
CarsAvailiable: string array of models are cars available
RentalSystem: Components of the vehicle that would be rented, its availability, and its history.
Attributes:
carStatus: a boolean that is true when the car is available to rent, false when otherwise
carColor: a string that contains the color of the car
carMake: a string that contains brand of the car
carModel: a string that contains the model of the car
carYear: a string that contains the year which the model of the car is from
carMileage: an integer that represents the mileage of the rental car
rentalHistory[]: a string array that contains the ID of previous owners of the car
Functions: 
rentCar(): changes the carStatus of a specific car to true, called when the car is being rented
returnCall(): changes the carStatus of a specific car to fales, called when the car is being returned
getInventory(): returns a array of strings that contains the carModel of the available cars in the rental system
Employee: Comprises additional information from the RentalSystem class that only employees are able to access. 
Attributes: 
numCars: an integer that represents the numbers of cars that are currently available at the rental location
carModel: a string that contains the model of the car
Functions:
addNewCar(): takes in a string parameter that represents the car model to add into the car inventory
manageRental(): allow access to the rental system to add, remove, or change rental status
viewContract(): takes in a string parameter that represents the customer ID and outputs the contract of customer
Users: These classes would contain information about users utilizing the system. 
Attributes:
name: string that represents the name of the user account
email: string that represents the email associated with the account
Functions:
newAccount(): creates a new account for new users
Employees: Connects directly to the users' class and consists of employees’ personal information.
Customers: Stems from user class and holds information about customers' payment information. 
Attributes:
ccNum: integer that represents the credit card number of user account
zipCode: integer that represents the zip code of user account
ccCVC: integer that represents the CVC code of credit card of user account
billingAddress: string that represents the address of the customer’s billing address

Integration Testing

