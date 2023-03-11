# javacode
# ASSIGNMENT 1

# QN 1.PRINT SUM,DIFFERENCE,PRODUCT,QOUTIENT AND REMAINDER OF TWO NUMBERS
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
# QN 2.PROGRAM TO COMPARE TWO NUMBERS
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
# QN 3.CONVERT STRING TO INTEGER
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

# QN 4.AREA OF RHOMBUS
```
public class Main
{
    public static void main(String args[])
    {
        float a=10,b=20;
        float Area_of_rhombus;
        Area_of_rhombus=(a*b)/2;
        System.out.println("Area of Rhombus is "+Area_of_rhombus);
    }
}
```
OUTPUT:
![QN 4](https://user-images.githubusercontent.com/114275126/224465494-874863cd-33ac-498e-b65e-93b291d5ab55.PNG)
/*

# QN 5.NUMBER OF DAYS IN MONTH
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {

        Scanner input = new Scanner(System.in);

        int Days=0;
        String Name = " ";

        System.out.print("Enter the month number: ");
        int month = input.nextInt();

        System.out.print("Enter the year: ");
        int year = input.nextInt();

        switch (month) {
            case 1:
                Name = "January";
                Days = 31;
                break;
            case 2:
                Name = "February";
                if ((year % 400 == 0)||((year % 4 == 0)&&(year % 100 != 0))) {
                    Days= 29;
                } else {
                    Days = 28;
                }
                break;
            case 3:
                Name = "March";
                Days = 31;
                break;
            case 4:
                Name = "April";
                Days = 30;
                break;
            case 5:
                Name = "May";
                Days = 31;
                break;
            case 6:
                Name = "June";
                Days = 30;
                break;
            case 7:
                Name = "July";
                Days = 31;
                break;
            case 8:
                Name = "August";
                Days = 31;
                break;
            case 9:
                Name = "September";
                Days = 30;
                break;
            case 10:
                Name = "October";
                Days = 31;
                break;
            case 11:
                Name = "November";
                Days = 30;
                break;
            case 12:
                Name = "December";
                Days = 31;
        }
        System.out.println(Name + " " + year + " has " + Days + " days");
    }
}
```

OUTPUT:
![QN 5](https://user-images.githubusercontent.com/114275126/224465700-54a486e3-7bcc-4d9a-8428-a5c42a8edd08.PNG)

# QN.6 EVEN NUMBERS FROM 1 TO 20

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
            Scanner input = new Scanner(System.in);
            int a = input.nextInt();
            for (int i=1; i<=a; i++)
            {
                if (i%2==0)
                {
                    System.out.print(i+" ");
                }
            }
        }
    }
 ```
    
 OUTPUT:
    ![QN 6](https://user-images.githubusercontent.com/114275126/224465822-8a6ed470-7f3e-461e-836c-9e56aacea682.PNG)
    
    
# QN.7 SIMPLE CALCULATOR

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        char operator;
        double num1, num2, result;
        Scanner input = new Scanner(System.in);
        System.out.println("Choose an operator: +, -, *, or /");
        operator = input.next().charAt(0);
        System.out.println("Enter first number");
        num1 = input.nextDouble();
        System.out.println("Enter second number");
        num2 = input.nextDouble();

        switch (operator) {

            case '+':
                result = num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + result);
                break;

            case '-':
                result = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + result);
                break;

            case '*':
                result = num1 * num2;
                System.out.println(num1 + " * " + num2 + " = " + result);
                break;

            case '/':
                result = num1 / num2;
                System.out.println(num1 + " / " + num2 + " = " + result);
                break;

            default:
                System.out.println("Invalid operator!");
                break;
        }
    }
}
```

OUTPUT:
![QN 7](https://user-images.githubusercontent.com/114275126/224465921-b004ade2-54e0-4a05-b40c-5078473e370a.PNG)

# QN 8.PRINT MULTIPLICATION TABLE OF A GIVEN NUMBER:

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n=s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(n+" * "+i+" = "+n*i);
        }
    }
}
```

OUTPUT:
![QN 8](https://user-images.githubusercontent.com/114275126/224465988-3ad453c0-e6f3-4672-8a8d-588cd5b39761.PNG)




    





