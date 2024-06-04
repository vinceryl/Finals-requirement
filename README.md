# Finals-requirement
public static void main(String[] args) {

 /* checked vs unchecked exception example */
 try { Class.forName("com.mcnz.Example"); // The code correctly uses a 'try-catch' block handlle the 'ClassNotFoundException'.//
 } catch (ClassNotFoundException e) {  // This is a checked exception, and proper handling ensures that the program doesn't crash unexpectedly. //
  System.out.println("Class was not found.");
 }
    
 String input = null;
 input.length(); // throws an unchecked exception
    
}
