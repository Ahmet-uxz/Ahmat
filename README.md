import java.util.Scanner;

public class teluryangdibeli {

    public static void main(String[] args) {
        Scanner inputan = new Scanner(System.in);
    System.out.print("Masukan (kg) telur yang dibeli: ");
    Double kiloTelur = inputan.nextDouble();

    System.out.print("Masukan Uang Bayar");
    Double uangBayar = inputan.nextDouble();

    double hargaTelur = kiloTelur * 28000;
    double kembalian = uangBayar - hargaTelur;

    System.out.println("Harga Telur per Kilogram: " + kembalian);
    }
}


import java.util.Scanner;

public class KonversiSuhu {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Masukkan suhu dalam Celcius: ");
        double celcius = scanner.nextDouble();

        double fahrenheit = (celcius * 9 / 5) + 32;

        System.out.printf("Suhu dalam Fahrenheit: %.2f%n", fahrenheit);

        scanner.close();
    }
}


import java.util.Scanner;

public class KelilingLingkaran {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Masukkan jari-jari lingkaran: ");
        double jariJari = scanner.nextDouble();

        double keliling = 2 * Math.PI * jariJari;

        System.out.printf("Keliling lingkaran: %.2f%n", keliling);

        scanner.close();
    }
}


import java.util.Scanner;

public class LuasPersegiPanjang {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Masukkan panjang persegi panjang: ");
        double panjang = scanner.nextDouble();

        System.out.print("Masukkan lebar persegi panjang: ");
        double lebar = scanner.nextDouble();

        double luas = panjang * lebar;

        System.out.printf("Luas persegi panjang: %.2f%n", luas);

        scanner.close();
    }
}


import java.util.Scanner;

public class VolumeKubus {
    public static void main(String[] args) {
          Scanner input = new Scanner(System.in);

        System.out.print("Masukkan panjang sisi kubus: ");
        double sisi = input.nextDouble();

        double volume = Math.pow(sisi, 3);

        System.out.println("Volume kubus dengan sisi " + sisi + " adalah: " + volume);
    }
}
