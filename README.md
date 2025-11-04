# Latihan-UKL-Sulit-2

Bagian 1 :

        public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("=== PROGRAM PENJUMLAHAN DUA MATRIKS ===");
        System.out.print("Masukkan jumlah baris: ");
        int baris = input.nextInt();
        System.out.print("Masukkan jumlah kolom: ");
        int kolom = input.nextInt();
        int[][] matriksA = new int[baris][kolom];
        int[][] matriksB = new int[baris][kolom];
        int[][] hasil = new int[baris][kolom];

kode ini adalah bagian awal dari program untuk menjumlahkan dua matriks.
Program ini menyiapkan ukuran matriks (baris dan kolom), lalu membuat tiga buah matriks:

Bagian 2 :

        System.out.println("\nMasukkan elemen-elemen Matriks A:");
        for (int i = 0; i < baris; i++) {
        for (int j = 0; j < kolom; j++) {
        System.out.print("A[" + i + "][" + j + "] = ");
        matriksA[i][j] = input.nextInt();
        }
        }

kode ini digunakan untuk mengisi nilai-nilai (elemen) matriks A berdasarkan input dari pengguna.
Setiap elemen matriks dimasukkan satu per satu melalui keyboard.

Bagian 3 : 

       System.out.println("\nMasukkan elemen-elemen Matriks B:");
       for (int i = 0; i < baris; i++) {
       for (int j = 0; j < kolom; j++) {
       System.out.print("B[" + i + "][" + j + "] = ");
       matriksB[i][j] = input.nextInt();
       }
       }
       for (int i = 0; i < baris; i++) {
       for (int j = 0; j < kolom; j++) {
       hasil[i][j] = matriksA[i][j] + matriksB[i][j];
       }
       }
       System.out.println("\n=== HASIL PENJUMLAHAN MATRIKS ===");
       for (int i = 0; i < baris; i++) {
       for (int j = 0; j < kolom; j++) {
       System.out.print(hasil[i][j] + "\t");
       }
       System.out.println();
       }

kode ini merupakan inti dari program penjumlahan dua matriks (A + B).
Fungsinya: Menginput elemen-elemen matriks B, Menjumlahkan matriks A dan B elemen per elemen, Menampilkan hasil penjumlahan dalam bentuk matriks hasil (C).

<img width="1261" height="647" alt="Screenshot 2025-11-05 001535" src="https://github.com/user-attachments/assets/f374b683-f106-4cc7-94ce-0247acd45b2f" />
