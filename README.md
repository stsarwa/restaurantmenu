# restaurantmenu
#include <stdio.h>
   
int main(){
	char input, ulang;

    printf("Selamat Datang di Restaurant Kami\n");
    printf("Apakah anda ingin memesan sesuatu (y/t) :");
    scanf(" %c", &ulang);
	
	while(ulang == 'y'){
		printf("----Selamat Datang di Restaurant Kami----\n");
		printf("----Berikut Daftar Menu---\n");
		printf("A. Paket Spesial\n");
		printf("B. Paket Promo\n");
		printf("C. Paket Hemat\n");
		printf("Pilih Menu yang Anda Inginkan : ");
		scanf(" %c", &input);
	
	    if (input == 'A' || input=='a'){
		    printf("Anda Memilih Paket Spesial, List Menunya Adalah:\n");
		    printf("1. Nasi Briyani Daging Ayam + Daging Unta\n");
		    printf("2. Jus Buah Naga + Empty Ice\n");
		    printf("3. Harga : Rp 150.000\n");
		
	    }else if (input == 'B' || input == 'b'){
		    printf("Anda Memilih Paket Promo, List Menunya Adalah :\n");
		    printf("1. Nasi Goreng Kampung + Daging Sapi + Telur\n");
		    printf("2. Ice Cream + Empty Ice\n");
		    printf("3. Harga : Rp. 45.000\n");
		
	    }else if (input == 'C' || input == 'c'){
		    printf("Anda Memilih Paket Promo, List Menunya Adalah :\n");
		    printf("1. Nasi Kari Daging Sapi\n");
		    printf("2. Jus Jeruk + Empty Ice\n");
		    printf("3. Harga : Rp. 20.000\n");
	    }
        printf("apakah anda ingin memesan lagi? (y/t) : ");
        scanf(" %c", &ulang);
    }
	if(ulang == 't'){
		printf("terimakasih sudah berkunjung :)");
	}
	
	return 0;
	}
	
