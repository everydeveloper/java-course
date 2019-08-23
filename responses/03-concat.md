## Step 9

Let's call the variables where our user input were stored and print them to the terminal:

Type the following code under Step 9.
```java
System.out.println();
System.out.println(firstName + " , your order is as follows: ");
System.out.println("_________________________________________");
System.out.println("Item Ordered: " + itemOrder);
System.out.println("Frosting: " + frostingType);
System.out.println("Filling: " + fillingType);
System.out.println("Toppings: " + toppings);
System.out.println("_________________________________________");
```

## Step 10:  

Now let's display the cost and sales tax of your order. Call the cost and tax rate numeric variables to calculate the total tax.  

Type the following code under Step 10.
```java
System.out.printf("The cost of your order is: $%.2f\n", cost);
tax = cost * TAX_RATE;
System.out.printf("The tax is: $%.2f\n", tax);
System.out.printf("The total due is: $%.2f\n",(tax + cost));
```

Notice the funny way we displayed the variables above `$%.2f\n` ?
These are special characters, used to indicate that the following variable is decimal, rounded to 2 places. 

Re-compile the java file `javac custom_order.java`, then run it `java custom_order` to make sure everything is working.

To finish up, let's *push this code to GitHub*, so you have have a reference.
```
git add custom_order.java
git commit -m"add cupcake shop"
git push origin master
```
