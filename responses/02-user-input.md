Alright, next let's take in some user input using our scanner object (which we called "keyboard")

The following code will ask the person what their name is, and create a personalized message for them to see the menu! The input entered in the terminal will be stored in the firstName variable.

### Step 3
Type the following code under Step 3.	  
```java
System.out.print("What is your first name? ");
firstName = keyboard.nextLine();

System.out.print(firstName + ", please see our MENU below: ");
System.out.print("\n"); // skips a line	  
```
Let's test it out!

Re-compile the java file `javac custom_order.java`, then run it `java custom_order`.

Notice how we can add variables to text with the plus symbol? 

### Step 4: 

You will display the menu by creating several print statements. 
Type the following code under Step 4. Modify spacing to align if needed:
```java
System.out.println("_______________________________________________");      
System.out.println("        MENU         QUANTITY    BASE COST  ");
System.out.println("_______________________________________________"); 
System.out.println("        Cake                     1            $15     ");
System.out.println("   Set of Cupcakes       6            $15     ");
System.out.println("_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _");
System.out.println("Frostings (vanilla, chocolate, strawberry, coco)");
System.out.println("Fillings (mocha, mint, lemon, caramel, vanilla)");
System.out.println("Toppings (sprinkles, cinnamon, cocoa, nuts)");
System.out.println("_______________________________________________");
```

### Step 5: 

Ask the user if they want to order cupcakes or a cake. (Only 1 for now for the sake of simplicity.) You will save the input item ordered in the itemOrder variable.

Type the following code under Step 5.
```java
System.out.println("Do you want CUPCAKES or a CAKE?");
itemOrder = keyboard.nextLine();
```

### Step 6: 

Ask the user what frosting they want based on the menu choices. You will save the input frosting in the frostingType variable.

Type the following code under Step 6.
```java
System.out.println("What type of FROSTING do you want? ");
System.out.println("Vanilla, Chocolate, Strawberry or Coco");
frostingType = keyboard.nextLine();
```

### Step 7: 

Ask the user what filling they want based on the menu choices. You will save the input filling in the filingType variable.

Type the following code under Step 7.
```java
System.out.println("What type of FILLING do you want? ");
System.out.println("Mocha, Mint, Lemon, Caramel or Raspberry");
fillingType = keyboard.nextLine();
```

### Step 8: 

Ask the user to choose toppings based on the menu choices. You will save the input toppings in the toppings variable.

Type the following code under Step 8.
```java
System.out.println("What type of TOPPINGS do you want? ");
System.out.println("Sprinkles, Cinnamon, Cocoa, Nuts");
toppings = keyboard.nextLine();
```

Re-compile the java file `javac custom_order.java`, then run it `java custom_order`.

You should see the series of questions above appear one at a time, waiting for user input.

*Close this issue to continue*
