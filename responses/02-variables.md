# Variables

In this section, you will create a scanner object to take in user input, declare variables that will store information, and print out a friendly message!

Type the following code under Step 2. It will create your scanner object, create your string variables that store text information, and double variables that store numeric values. Most of these variables don't have any values yet (except "cost" and "TAX_RATE"). We are just declairing their name and data type.

The Scanner object has pre-built methods we will use to process user input. Notice how we imported it at the top of the file? 

```java
Scanner keyboard = new Scanner (System.in); 

String firstName; // User's first name
String itemOrder; // Item ordered
String frostingType; // Frosting ordered
String fillingType; // Filling ordered
String toppings; // Toppings ordered
String input;  // User input

double cost = 15.00; // Cost of cake and cupcakes
final double TAX_RATE = .08;  // Sales tax rate
double tax; // Amount of tax
```
Add in the following comment and line of code to print friendly messages: 
```java
// Introduce shop and prompt user to input first name

System.out.println("Welcome to Java's Cake & Cupcake Shop!");
System.out.println("We make custom cakes with our secret cake batter!");
```

Before we test this code, remember to re-compile the java file
`javac custom_order.java`
Then run the file with this command:
`java custom_order`

If you see our friendly greeting in your terminal, *add a comment to this issue.* 