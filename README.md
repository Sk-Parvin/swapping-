# swapping-
#Using a temporary variable
#java

import java.util.Scanner;
public class SwapNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();
        System.out.println("Before swapping: num1 = " + num1 + ", num2 = " + num2);
        int temp = num1;
        num1 = num2;
        num2 = temp;
        System.out.println("After swapping: num1 = " + num1 + ", num2 = " + num2);
        canner.close();
    }
}



#python
#usingn a temporary variable
# Swapping two numbers using a temporary variable

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
print(f"Before swapping: num1 = {num1}, num2 = {num2}")
temp = num1
num1 = num2
num2 = temp
print(f"After swapping: num1 = {num1}, num2 = {num2}")



#swapping
#without using temporary variable
#java

import java.util.Scanner;
public class SwapNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();
        System.out.println("Before swapping: num1 = " + num1 + ", num2 = " + num2);
        num1 = num1 + num2;
        num2 = num1 - num2;
        num1 = num1 - num2;
        System.out.println("After swapping: num1 = " + num1 + ", num2 = " + num2);
        scanner.close();
    }
}



#python 
#without using a temporary variable


# Swapping two numbers without using a temporary variable
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
print(f"Before swapping: num1 = {num1}, num2 = {num2}")
num1, num2 = num2, num1
print(f"After swapping: num1 = {num1}, num2 = {num2}")

