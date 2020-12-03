# Kontrolnaya
import java.util.Scanner;

public class kontrolnaya {
   public static boolean aPlusB(double a, double b){
        return (a+b<=20&a+b>=10);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("1 задание");
        double a = sc.nextDouble();
        double b = sc.nextDouble();
        System.out.println(aPlusB(a,b));



        System.out.println("2 задание");
        int[] arr= new int[8];
        int ab = 0;
        for (int i = 0; i < arr.length; i++) {
            arr[i]= ab;
            ab+=3;
        }
        for (int value : arr) {
            System.out.print(value + " ");
        }



        System.out.println("\n 3 задание");
        int[] arr1 ={ 1, 5, 3, 2, 11, 4, 5, 2, 4, 8, 9, 1};
        for (int i = 0; i < arr1.length; i++) {
            if (arr1[i]<6)
                arr1[i]=arr1[i]*2;
        }
        for (int value : arr1) {
            System.out.print(value + " ");
        }
    }
}
