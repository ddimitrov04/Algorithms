import java.util.Scanner;


public class River {

    public static void main(String[] args) {

        Scanner Input = new Scanner(System.in);
        System.out.println("Input sum : ");
        int Sum = Input.nextInt();

        CountNominees(Sum);
    }

    public static void CountNominees(int sum) {
        int counter = 0;
        int index = 0;
        int[] nominees = {50, 20, 10, 5, 2, 1};

        while (sum > 0) {
            if (nominees[index] <= sum) {
                sum = sum - nominees[index];
                counter++;
                System.out.println(sum + nominees[index] + "(-" + nominees[index] + "); Counter : " + counter);

            } else {
                if (index + 1 < nominees.length) {
                    index++;
                } else {
                    System.out.println("There is no other nominees for this Sum : " + sum);
                    break;
                }
            }
        }
        System.out.println("Number of coins is :" + counter);
    }
}
