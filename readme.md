TAKSİMETRE

import java.util.Scanner;

public class Main {
public static void main(String[] args) {
int km;
double perKm = 2.20, total, starPrice =10;

        Scanner input = new Scanner(System.in);
        System.out.print("Mesafeyi KM cinsinden giriniz : ");
        km = input.nextInt();

        total = (km*perKm);
        total += starPrice;

        total = (total<20) ? 20 : total;
        System.out.println("Toplam Tutar : " + total + " Tl");
    }
}