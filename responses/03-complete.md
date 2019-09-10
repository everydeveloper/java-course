🌟⭐🌟⭐Congratulations!⭐🌟⭐🌟

You created your first Java program!☕😀 This is the end of this intro course. If you would like to continue working on your cupcake shop, here are some potential next steps:

Next Steps:
* Declair a "totalCost" variable, and a "addOnList" variable
```java
int totalCost
String addOnList
```
* Write a custom method that takes a string and integer as arguments, then adds them to our cost and addOnList variables
```java
static void addOn(String item, int cost) {
  totalCost+=cost;
  addOnList+=item;
}
```
* Write *if statements* before each add-on to see if they want that add-on (ex: do you want filling? We have ... ). If they respond with anything but "no", call your addItem method with their input and a cost as arguments. 
```java
if (frostingType != "no"){
  addItem(frostingType,2);
  addOnList+=", ";
}
```
* Modify the finial statement so it displays the new cost variable and addOnList statement.
