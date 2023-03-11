# javacode
ASSIGNMENT 1
QN 1.PRINT SUM,DIFFERENCE,PRODUCT,QOUTIENT AND REMAINDER OF TWO NUMBERS
```
import java.util.Scanner;
                 
public class JavaProgram
{
    public static void main(String args[])
  {
    int first, second, add, subtract, multiply,remainder;
    float divide;
    Scanner scanner = new Scanner(System.in);

    System.out.print("Enter Two Numbers : ");
    first = scanner.nextInt();
    second = scanner.nextInt();

    add = first + second;
    subtract = first - second;
    multiply = first * second;
    divide = (float) first / second;
    remainder= first%second;

    System.out.println("Sum = " + add);
    System.out.println("\nDifference = " + subtract);
    System.out.println("Multiplication = " + multiply);
    System.out.println("Division = " + divide);
    System.out.println("Remainder= "+remainder);
    
  }
}
```
OUTPUT
![qnqn](https://user-images.githubusercontent.com/114275126/224463823-f79535f1-ce59-4717-90ec-e56a98197814.PNG)

/*
QN 2.PROGRAM TO COMPARE TWO NUMBERS
```
import java.util.Scanner;
public class Main 
{
    public static void main(String[] args)
    {
        int a,b;
        Scanner in = new Scanner(System.in);
        a = in.nextInt();
        b = in.nextInt();
        if(a==b)
        {
            System.out.println("Two Numbers are Equal");
        }
        if(a!=b)
        {
            System.out.println("Two Numbers are Not Equal");
        }
        if(a>b)
        {
            System.out.println("A is Greater than B");
        }
        if(a<b)
        {
            System.out.println("A is Less than B");
        }
        

    }
}
```
OUTPUT:
![QN 2](https://user-images.githubusercontent.com/114275126/224464729-a623d940-54f1-4145-85b4-c8b4354e429d.PNG)

*/
/*QN 3.CONVERT STRING TO INTEGER
PROGRAM 
```
public class Main 
{
    public static void main(String[] args)
    {
        String a="50";
        int b=Integer.parseInt(a);
        System.out.println("Convert a string to an integer "+b);
    }
    
}
```
OUTPUT:
![QN 3](https://user-images.githubusercontent.com/114275126/224464769-0cb48d86-59a2-4054-9c50-224aac898043.PNG)

*/

