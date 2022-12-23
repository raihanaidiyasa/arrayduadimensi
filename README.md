# Ujian Akhir Semester 
<br>Mata Kuliah 	: Teknik Informatika
<br>Nama		      : Raihan Aidiyasa Shadiq
<br>NIM		        :	1227050112
<br>Jurusan		    :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
   Pada array dua dimensi, kita akan mencoba untuk menukar inputan baris dan kolom, dan juga menampilkan angka-angka yang kita ingin tampilkan.
## Source Code
   #1. Menukar inputan baris dan kolom
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
	#2. Menampilkan angka yang ingin ditampilkan (yang habis dibagi 3, 5, dan 7)
	#include <iostream>
using namespace std;

int main(){
	cout << "==========================================" << endl;
	cout << "Program mencari angka kelipatan 3, 5, dan 7" << endl;
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
  
  cout << "Hasil angka yang habis dibagi dengan 3, 5, dan 7: " << endl << endl;
 
  for(i = 0; i < jumlahBaris ; i++){
    for(j = 0; j < jumlahKolom; j++){
    	if (array[i][j] % 3 == 0 && array[i][j] % 5 == 0 && array[i][j] % 7 == 0){
		
      		cout << array[i][j] << "  ";
      	}
    }
	}
}
## Output
   ![image](https://user-images.githubusercontent.com/119490191/209351254-fd9d69fe-3575-412e-a409-966ec2742f34.png)
   ![image](https://user-images.githubusercontent.com/119490191/209351637-b19db944-e8dc-4481-9408-3350f7fafae6.png)

