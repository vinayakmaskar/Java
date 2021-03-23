import java.util.Scanner;

public class Fibonacci {

    public static void main(String[] args) {
        int a = 0, b = 1, c, count = 0, n1;

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter how many terms you want to get of fibonacci series : ");
        n1 = sc.nextInt();

        if (n1 <= 0) {
            System.out.println("Please enter any positive integer ");
        }

        else {
            System.out.println("Fibonacci series is : ");
            while (count < n1) {

                System.out.println(a);
                c = a + b;
                a = b;
                b = c;
                count += 1;
            }
        }
    }
}
