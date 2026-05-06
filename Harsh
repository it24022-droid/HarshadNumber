import java.util.Scanner;
public class HarshadNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Take a input");
        int x = sc.nextInt();
        int sumDigits = 0;
        int temp = x;
        // logic of  summition
        while (temp > 0) {
            sumDigits += temp %10; // adding last number
            temp /= 10; // deleting last digit
            
        } 
        // is it hash number chaking 
        if(x % sumDigits == 0) {
            System.out.println(x + "It is a hash number");
            
        } 
        else {
            System.out.println(x+ "It is not hash number");
            
        }
        sc.close();
        
    }
}
