import java.util.Scanner;

public class DersOrtalamasiHesaplama {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Matematik sınav puanını girin:");
        double matematik = scanner.nextDouble();

        System.out.println("Fizik sınav puanını girin:");
        double fizik = scanner.nextDouble();

        System.out.println("Kimya sınav puanını girin:");
        double kimya = scanner.nextDouble();

        System.out.println("Türkçe sınav puanını girin:");
        double turkce = scanner.nextDouble();

        System.out.println("Tarih sınav puanını girin:");
        double tarih = scanner.nextDouble();

        System.out.println("Müzik sınav puanını girin:");
        double muzik = scanner.nextDouble();

        double ortalama = (matematik + fizik + kimya + turkce + tarih + muzik) / 6;

        System.out.println("Derslerin ortalama puanı: " + ortalama);

        if (ortalama >= 60) {
            System.out.println("Sınıfı Geçti");
        } else {
            System.out.println("Sınıfta Kaldı");
        }
    }
}
