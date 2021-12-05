# StockInventory System

## How to run the application

1. On running the applicaton, the user will be prompted to enter the path of stock input file (Dataset.csv).
2. Then the user will be prompted to enter the path of the order input file (InputFile.csv).
3. Then the user will be prompted to specify the path where he/she wants to store the output/error file.
4. The system will validate the order items and generate an error file if it encounters any problems.
5. If no errors were found, the system will create a success file with the total amount spent.
6. To create a new order, the user needs to start the application again.

# Design Patterns Used

* Singleton Design Pattern - Class StockDatabase
* Factory Design Pattern - 
  * Abstract Class Category, Class Essentials, Class Item, Class Luxury
  * Interface OutputFile, Class ErrorFile, Class SuccessFile and Clas FileHandler
* Iterator Pattern - CLass FileRepository, Class Container, Class Iterator, Class OrderController

# Class Diagram
