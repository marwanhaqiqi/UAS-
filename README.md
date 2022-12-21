# UAS-
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		: Gallung Marwan Haqiqi Hafidz
<br>NIM		:	1227050049
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Modulo merupakan operator sisa dari pembagian yang disimbolkan dengan % 
Contoh program sebagai berikut :
1) Modulo dari 14%5
Pembahasan : 14%5 = 2 sisanya 4, maka 14%5 = 4
2) Modulo dari 16%2
Pembahasan : 16%2 = 6 sisanya 0, maka 14%5 = 0
3) Modulo dari 24%48
Pembahasan : 24%48 = 0 sisanya 24, maka 24%48 = 24
4) Modulo dari 0%7
Pembahasan : 0%7 = 0 sisanya 0, maka 0%7 = 0
5) Modulo dari -8%3
Pembahasan : -8%3 = -2 sisanya -2, maka -8%3 = -2
6) Modulo dari 15%-2
Pembahasan : 15%-2 = -7 sisanya 1, maka 15%-2 = 1
7) Modulo dari -3%5
Pembahasan : -3%5 = 0 sisanya -3, maka -3%5 = -3
8) Modulo dari 5%-9
Pembahasan : 5%-9 = 0 sisanya 5, maka 5%-9 = 5

## Source Code
#include <iostream>

using namespace std;

int main()
{
     //2. Deret matematika bilangan yang habis dibagi 3 5 dan 7
    //Menginput banyaknya baris 0-50
    //Menginput banyaknya kolom
    //Menampilkan bilangan yang habis dibagi 3,5 dan 7
    int array[50][50], baris, kolom;
    cout << "Masukkan jumlah baris : ";
	cin >> baris;
    cout << "Masukkan jumlah kolom : ";
	cin >> kolom;
    cout << "Masukkan nilai : " << endl;
    for(int i = 0; i < baris ;i++){
        for(int j = 0; j < kolom ;j++){
            cout << "Tentukan nilai baris ke-" << i+1 << " dan kolom ke-" << j+1 << " : ";
            cin >> array[i][j];
        }
    }
    cout << "Nilai awalnya adalah :" << endl;
    for(int i = 0; i < baris ;i++){
        for(int j = 0; j < kolom ;j++){
            cout << array[i][j] << " ";
        }
        cout << endl;
    }
    cout << "Nilai akhirnya adalah :" << endl;
    for(int i = 0; i < baris ;i++){
            for(int j = 0; j < kolom ;j++){
                if(array[i][j]%3 == 0 || array[i][j]%5 == 0 || array[i][j]%7 == 0){
                    cout << array[i][j] << " ";
                }
                else{
                }
            }
    }
    return 0;
}

## Output
![image](https://user-images.githubusercontent.com/121102747/208852668-71e7e1b9-edb8-4291-b0dc-ec10f1a31e80.png)
