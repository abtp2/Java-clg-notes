# Question
Print the all prime numbers between 1 to the given number `n`

```java
import java.util.Scanner;

public class Main{
  public static void main(String[] args){
    Scanner scanner = new Scanner(System.in);
    System.out.print("Enter a number: ");
    int n = scanner.nextInt();

    for(int i=2; i<=n; i++){
      boolean isPrime = true;
      for(int j=2; j<=Math.sqrt(i); j++){
        if(i%j==0) isPrime=false;
      }
      if(isPrime) System.out.println(i);
    }
  }
}
```