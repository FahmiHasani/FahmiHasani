#include <stdio.h>

int main() {
    int num1, num2, sum;

    // Meminta pengguna untuk memasukkan dua angka
    printf("Masukkan angka pertama: ");
    scanf("%d", &num1);
    printf("Masukkan angka kedua: ");
    scanf("%d", &num2);

    // Menghitung jumlah
    sum = num1 + num2;

    // Menampilkan hasil
    printf("Jumlah dari %d dan %d adalah %d\n", num1, num2, sum);

    return 0;
