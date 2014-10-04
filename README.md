tugas2-algoritma
================

#include &lt;stdio.h> main() { float s, r, t, hasil; int jenis; char back; printf("			Program untuk menghitung

"); printf("Pilih program yang anda inginkan: 
"); printf("1. Menghitung volume kubus
"); printf("2. Menghitung luas lingkaran
"); printf("3. Menghitung volume silinder
"); printf("Masukkan pilihan anda : "); scanf("%d", &amp;jenis); switch(jenis) { case 1: printf("Masukkan panjang sisi kubus : "); scanf("%f", &amp;s); hasil=s*s*s; printf("Volume kubus : %2.2f cm3
", hasil); break; case 2: printf("Masukkan panjang jari-jari lingkaran : "); scanf("%f", &amp;r); hasil=3.14*r*r; printf("Luas lingkaran : %2.2f cm2
", hasil); break; case 3: printf("Masukkan panjang jari-jari lingkaran : "); scanf("%f", &amp;r); printf("Masukkan tinggi silinder : "); scanf("%f", &amp;t); hasil=3.14*r*r*t; printf("Volume silinder : %2.2f cm3
", hasil); break; default: printf("MAAF KODE YANG ANDA MASUKKAN SALAH
"); } }
