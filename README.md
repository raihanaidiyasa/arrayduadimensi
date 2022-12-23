# Ujian Akhir Semester 
<br>Mata Kuliah 	: Teknik Informatika
<br>Nama		      : Raihan Aidiyasa Shadiq
<br>NIM		        :	1227050112
<br>Jurusan		    :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
   Pada array dua dimensi, kita akan mencoba untuk menukar inputan baris dan kolom, dan juga menampilkan angka-angka yang kita ingin tampilkan.
## Source Code
   #include <iostream>
using namespace std;

int main(){
	cout << "==========================================" << endl;
	cout << "Program membalik baris dan kolom" << endl;
  cout << "==========================================" << endl;
  cout << "Nama	: Raihan Aidiyasa Shadiq" << endl;
  cout << "NIM	: 1227050112" << endl;
  cout << "Kelas	: IF - 1C" << endl;
  cout << "==========================================" << endl;
 
  int array[150][150];
  int jumlahBaris, jumlahKolom, i, j;
 
  cout << "Input jumlah baris: ";
  cin >> jumlahBaris;
 
  cout << "Input jumlah kolom: ";
  cin >> jumlahKolom;
  cout << endl;
 
  for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
      cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
      cin >> array[i][j];
    }
    cout << endl;
  }
  cout << "Hasil array: " << endl;
 
  for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
      cout << "  " << array[i][j] << "  ";
    }
    cout << endl;
  }
  cout << endl << "Hasil array ketika baris dan kolom ditukar: " << endl;
 
  for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
      cout << "  " << array[j][i] << "  ";
    }
    cout << endl;
  }
}
## Output
