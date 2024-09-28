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

        // Meminta input suhu dalam Celcius
        System.out.print("Masukkan suhu dalam Celcius: ");
        double celcius = scanner.nextDouble();

        // Menghitung suhu dalam Fahrenheit
        double fahrenheit = (celcius * 9 / 5) + 32;

        // Menampilkan hasil
        System.out.printf("Suhu dalam Fahrenheit: %.2f%n", fahrenheit);

        scanner.close();
    }
}


import java.util.Scanner;

public class KelilingLingkaran {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Meminta input jari-jari lingkaran
        System.out.print("Masukkan jari-jari lingkaran: ");
        double jariJari = scanner.nextDouble();

        // Menghitung keliling lingkaran
        double keliling = 2 * Math.PI * jariJari;

        // Menampilkan hasil
        System.out.printf("Keliling lingkaran: %.2f%n", keliling);

        scanner.close();
    }
}


import java.util.Scanner;

public class LuasPersegiPanjang {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Meminta input panjang persegi panjang
        System.out.print("Masukkan panjang persegi panjang: ");
        double panjang = scanner.nextDouble();

        // Meminta input lebar persegi panjang
        System.out.print("Masukkan lebar persegi panjang: ");
        double lebar = scanner.nextDouble();

        // Menghitung luas persegi panjang
        double luas = panjang * lebar;

        // Menampilkan hasil
        System.out.printf("Luas persegi panjang: %.2f%n", luas);

        scanner.close();
    }
}


import java.util.Scanner;

public class VolumeKubus {
    public static void main(String[] args) {
        // Membuat scanner untuk input dari pengguna
        Scanner input = new Scanner(System.in);

        // Meminta pengguna memasukkan panjang sisi kubus
        System.out.print("Masukkan panjang sisi kubus: ");
        double sisi = input.nextDouble();

        // Menghitung volume kubus
        double volume = Math.pow(sisi, 3);

        // Menampilkan hasil
        System.out.println("Volume kubus dengan sisi " + sisi + " adalah: " + volume);
    }
}
