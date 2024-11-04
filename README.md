# java-ManavKasaProgrami
import java.util.Scanner;
import java.util.Locale;

public class ManavKasaProgrami {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        scanner.useLocale(Locale.FRANCE);

        double armutFiyat = 2.14;
        double elmaFiyat = 3.67;
        double domatesFiyat = 1.11;
        double muzFiyat = 0.95;
        double patlicanFiyat = 5.00;


        System.out.print("Armut Kaç Kilo? :");
        double armutKilo = scanner.nextDouble();

        System.out.print("Elma Kaç Kilo? :");
        double elmaKilo = scanner.nextDouble();

        System.out.print("Domates Kaç Kilo? :");
        double domatesKilo = scanner.nextDouble();

        System.out.print("Muz Kaç Kilo? :");
        double muzKilo = scanner.nextDouble();

        System.out.print("Patlıcan Kaç Kilo? :");
        double patlicanKilo = scanner.nextDouble();

        double toplamTutar = (armutKilo * armutFiyat) + (elmaKilo * elmaFiyat) +
                             (domatesKilo * domatesFiyat) + (muzKilo * muzFiyat) +
                             (patlicanKilo * patlicanFiyat);

        System.out.printf("Toplam Tutar. %.2f TL", toplamTutar);
    }
}
