//Daily tasks (50 programs)
/*1) positive or negative:
import java.util.Scanner;
public class q{
  public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter number: ");
    int num = sc.nextInt();
    if (num >= 0){
      System.out.println("Positive");
    }else{
      System.out.println("Negative");
    }
    sc.close();
  }
}

//2) leap year:
import java.util.Scanner;

public class q {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a year: ");
        int year = sc.nextInt();

        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            System.out.println(year + " is a leap year");
        } else {
            System.out.println(year + " is not a leap year");
        }

        sc.close();
    }
}

//4) pass or fail:

import java.util.Scanner;
public class q{
  public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter your marks: ");
    int marks = sc.nextInt();
    if (marks >= 35){
      System.out.println("Pass");
      }if (marks >= 90){
        System.out.println("Grade A");

      }else if (marks >= 70){
        System.out.println("Grade B");
      }else if (marks >= 50){
        System.out.println("Grade c");
      }
      else if (marks >= 36){
        System.out.println("Grade D");
        }else{
      System.out.println("Fail");
      sc.close();
    }
    
  }
}

// L)for loop - sum of a given range:
public class number{
    public static void main(String args[]){
        int sum = 0;
        for (int i = 1;i<=8;i++){
            sum = sum+=i;
            System.out.println(sum);
        }
    }
}

// L)Range using while loop
public class q{
  public static void main(String args[]){
    int i = 1;
    while (i <= 50){
      System.out.println(i);
      i++;
    }
  }
}

 L) Printing hello:
 public class hello{
    public static void main(String args[]){
        int i = 1;
        while (i<=20){
            System.out.println("Hello");
            i++;
        }
    }
}

//L)Printing even numbrs with while loop 
public class q{
  public static void main(String args[]){
    int i = 2;
    while(i <= 100){
      System.out.println(i);
      i+=2;
    }
  }
}


//L) Multiplication table from user:
import java.util.Scanner;
public class q{
  public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter a number for getting its table: ");
    int num = sc.nextInt();
    for (int i = 1;i <= 12;i++){
      System.out.println(num + "*" + i + "=" + (num* i));
      sc.close();

    }
    


  }
}

// 7) Squares of 20:
public class q{
  public static void main(String args[]){
    for (int i = 1; i <= 20; i++){
      System.out.println(i*i);
    }
  }
}

//8) n even numbers ;
import java.util.Scanner;
public class q{
  public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter a number to get even numbers: ");
    int num = sc.nextInt();
    for (int i = 2; i <= num; i +=2){
      System.out.println(i);

    }
  }
}

// 9. Print sum of all even numbers b/w 1 to n
import java.util.Scanner;
public class q{
  public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter a number: ");
    int num = sc.nextInt();
    int sum = 0;
    for (int i = 2; i <= num; i += 2){
      sum = sum + i;}

      System.out.println(sum);
     
    sc.close();
  }
}*/

