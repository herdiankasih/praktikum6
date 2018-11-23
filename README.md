# praktikum6

Latihan :

Program sederhana operasi kalkulator (penjumlahan, pengurangan, perkalian, dan pembagian) dengan menginputkan 2 buah bilangan

=>> Alur algoritma :

1. Mulai program.
2. Masukkan bilangan a dan b.
3. Masukkan pilihan operasi sebagai berikut,
	"1" untuk penjumlahan
	"2" untuk pegurangan
	"3" untuk perkalian
	"4" untuk pembagian
4. Jika input 1 maka hitung hasil=a+b dan cetak hasilnya.
5. Jika input 2 maka hitung hasil=a-b dan cetak hasilnya.
6. Jika input 3 maka hitung hasil=a*b dan cetak hasilnya.
7. Jika input 4 maka hitung hasil=a/b dan cetak hasilnya.
8. Program end.


=>> kode C++ program :

#include <iostream>
#include <cstdlib>

using namespace std;

int main() {

    float a,b;
    int kode;

    menu :
    cout << "Kalkulator Sederhana C++ \n";

    cout << "Pilih Operasinya : \n";
    cout << "1.Penjumlahan (+)\n";
    cout << "2.Pengurangan (-)\n";
    cout << "3.Perkalian (*)\n";
    cout << "4.Pembagian (/)\n\n";
    cout << "Masukkan Pilihan : ";cin >> kode;
    if (kode > 4 || kode < 1){
        cout << "\nKode yang anda masukkan tidak ada \nSilahkan masukkan ulang kode .";
        system("pause");
        system("cls");
        goto menu;
    }
    else {
        cout << "Masukkan angka pertama : ";cin >> a;
        cout << "Masukkan angka kedua   : ";cin >> b;
        if (kode == 1){
            cout << "\nHasil penjumlahan dari "<<a<<" + "<<b<<" adalah : "<<a+b<<endl;
        }
        else if (kode == 2){
            cout << "\nHasil pengurangan dari "<<a<<" - "<<b<<" adalah : "<<a-b<<endl;
        }
        else if (kode == 3){
            cout << "\nHasil perkalian dari "<<a<<" * "<<b<<" adalah : "<<a*b<<endl;
        }
        else if (kode == 4){
            cout << "\nHasil pembagian dari "<<a<<" / "<<b<<" adalah : "<<a/b<<endl;
        }
    }

    return 0;
}


=>> Hasil screenshoot program :



![flowchart_praktikum6](https://user-images.githubusercontent.com/43899109/48949708-83687400-ef6b-11e8-9188-c4b44e724517.jpg)


![hasil1](https://user-images.githubusercontent.com/43899109/48949710-83687400-ef6b-11e8-9c8b-10ddfd5b618f.jpg)


![hasil2](https://user-images.githubusercontent.com/43899109/48949711-84010a80-ef6b-11e8-8e8e-866079088af6.jpg)


![hasil3](https://user-images.githubusercontent.com/43899109/48949712-84010a80-ef6b-11e8-903f-60ea304557ff.jpg)


![hasil4](https://user-images.githubusercontent.com/43899109/48949713-8499a100-ef6b-11e8-8328-03d9d2cbafd3.jpg)
