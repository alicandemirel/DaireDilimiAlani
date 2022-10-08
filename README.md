//DaireDilimiAlani

import java.util.Scanner;

public class DiareninAlanı {

    public static void main(String[] args) {

        int r;
        double a, alan, pi = 3.14;

        Scanner input = new Scanner(System.in);

        System.out.print("Yarıçapı giriniz: ");
        r = input.nextInt();
        System.out.print("Merkez açıyı giriniz: ");
        a = input.nextInt();

        alan = (pi * (r*r) * a) / 360;

        System.out.print("Daire diliminin alanı: " + alan);

    }
}
