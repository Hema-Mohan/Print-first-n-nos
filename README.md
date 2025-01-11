# Print-first-n-nos
import java.util.Scanner;

Public class PrintNumbers {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the value of n: ");
        int n = sc.nextInt();

        System.out.println("The first " + n + " numbers are:");
        for (int i = 1; i <= n; i++) {
            System.out.print(i + " ");
        }
    }
}

OUTPUT:

Enter the value of n: 5
The first 5 numbers are:
1 2 3 4 5
