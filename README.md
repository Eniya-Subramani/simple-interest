# simple-interest
package simple.interest;
import java.util.Scanner;
public class SimpleInterest {
    public static void main(String[] args) {
         Scanner scan=new Scanner(System.in);
        System.out.println("Enter the principal amount :");
        double principal = scan.nextDouble();
        System.out.println("Enter the annual rate of interest (in %)");
        double rate = scan.nextDouble();
        System.out.println("Enter the time (in years):");
        double time = scan.nextDouble();
        double simpleinterest=(principal*rate*time)/100;   
        System.out.println("The Simple Interest is :" + simpleinterest);
         }
   }
Output:

Enter the principal amount :
10000
Enter the annual rate of interest (in %)
5
Enter the time (in years):
2
The Simple Interest is :1000.0
