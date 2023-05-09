HomeWork5
// Java code to illustrate
// HashSet.remove() method
// over String Elements

// Importing required classes
import java.util.*;

// Main class
// HashSet demo
public class GFG {

// Main driver method
public static void main(String args[])
{

// Creating an empty HashSet
// Declaring object of string type
HashSet<String> set = new HashSet<String>();

// Adding custom input elements into the Set
// using add() method
set.add("Welcome");
set.add("To");
set.add("Geeks");
set.add("For");
set.add("Geeks");

// Displaying the HashSet(object elements)
System.out.println("HashSet: " + set);

// Removing elements
// using remove() method
set.remove("Geeks");
set.remove("For");
set.remove("Welcome");

// Now displaying the HashSet after removal
// of elements from it
System.out.println(
"HashSet after removing elements: " + set);
}
}
