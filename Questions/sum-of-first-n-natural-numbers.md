# Question
Write a program to print sum of `n` natural numbers 

**Method-1:** using loop
```java
import java.util.Scanner;

public class Main{
  public static void main(String[] args){
    Scanner scanner = new Scanner(System.in);
    System.out.print("Enter a number: ");
    int n = scanner.nextInt(); 
    int sum = 0;
    for(int i=1; i<=n; i++){
      sum += i;
    }
    System.out.println("sum=" + sum);
  }
}
```


**Method-2:** using mathematical formula
```java
import java.util.Scanner;

public class Main{
  public static void main(String[] args){
    Scanner scanner = new Scanner(System.in);
    System.out.print("Enter a number: ");
    int n = scanner.nextInt(); 
    int sum = n*((n+1)/2);
    System.out.println("sum=" + sum);
  }
}
```