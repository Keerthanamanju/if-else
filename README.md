import java.util.Scanner;

class IfElse {
    public static void main(String[] args) {
        // Create a Scanner object for user input
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter a number
        System.out.print("Enter a number: ");
        int num = scanner.nextInt();

        // Check if the number is even or odd
        if (num % 2 == 0) {
            System.out.println("The number is even.");
        } else {
            System.out.println("The number is odd.");
        }

        // Close the scanner
        scanner.close();
    }
}


OUTPUT:



OUTPUT:
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> javac hello.java
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> java hello.java
The number is even
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1
