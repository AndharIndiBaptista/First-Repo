//First-Repo
//Repo pertama

#include <stdio.h>

int main() {
    int Menu, pilihan, btc, eth, usdt, hasil;
    
    printf("Selamat datang Asdos mata kuliah ASD\ndi program Konversi uang dengan pilihan sebagai berikut:\n");
    Menu;
    printf("1. Bitcoin ke Rupiah\n");
    printf("2. Etherium ke Rupiah\n");
    printf("3. Dollar ke Rupiah\n");
    printf("Masukkan pilihan Anda: ");
    scanf("%d", &pilihan);
    
    if(pilihan=1){
        system ("cls");
        printf("Selamat datang di konversi Bitcoin ke Rupiah.\n");
        printf("Silahkan masukkan nominal Bitcoin: ");
        scanf("%d", &btc);
        hasil=btc*547974483;
        printf("Hasil= Rp%d", hasil);
    }
    
    
    return 0;
}
