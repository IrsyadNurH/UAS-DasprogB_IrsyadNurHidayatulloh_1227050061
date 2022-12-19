# UASDasarPemograman_IrsyadNurHidayatulloh_1227050061
UAS DASAR PEMORGRAMAN

# Ujian Akhir Semester 
<br>Mata Kuliah 	:Dasar Pemograman     
<br> Nama		:Irsyad Nur Hidayatulloh
<br>NIM		:	1227050061
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Array dua dimensi merupakan array yang terdiri dari m buah baris dan n buah kolom. Bentuknya dapat berupa matriks atau tabel.
Matriks merupakan kumpulan-kumpulan bilangan yang disusun secara baris (vertikal) dan kolom (horizontal) bisa disebut juga array dua dimensi (multi-dimensional). perkalian matriks memiliki syarat yaitu jumlah kolom matriks pertama sama dengan jumlah baris matriks kedua.Kemudian disini juga harus menampilkan sebuah angka yang habis di bagi 3 , 5 dan 7.

## Source Code

    //1. Input, bnyknya baris kolom banyak baris dan banyak data tukar baris jadi kolom , kolom jadi baris
                      



    #include <iostream>
    using namespace std;

    int main(){

        cout << " Irsyad Nur Hidayatulloh" << endl;
        cout << " 1227050061 " << endl;
        cout << " IF-B " << endl
             << endl;

    int i, j, m, n, matriks[10][10], transpose[10][10];

    cout << "Masukkan jumlah baris yang diinginkan: ";
    cin >> m;
    cout << "Masukkan jumlah kolom yang diinginkan: ";
    cin >> n;

    cout << "Masukkan nilai\n";
    for (i = 0; i < m; i++){
      for (j = 0; j < n; j++){
        cin  >> matriks[i][j];
      }
    }

    for (i = 0; i < m; i++){
      for (j = 0; j < n; j++){
        transpose[j][i] = matriks[i][j];
      }
    }

    cout << "Hasil pertukaran Matriks: \n";
    for (i = 0; i < n; i++){
      for (j = 0; j < m; j++){
        cout << transpose[i][j] << "\t";
      }
      cout << endl;
    } 
    }

   
   //2. Baris dan kolom tentukan banyaknya dan isikan data dan beda akhirnya, tampilkan bilangan habis dibagi 3,5,7


            #include <iostream>
            using namespace std;

            const int MAX_ROWS = 100;
            const int MAX_COLS = 100;

            int main()
            {
              cout << "Nama  : Irsyad Nur Hidayatulloh^" << endl;
              cout << "NIM   : 1227050061^ " << endl;
              cout << "Kelas : IF-B^" << endl;
              cout << "==========================================" << endl;
              cout << "Program C++ Input Matriks 2 Dimensi^" << endl;
              cout << "==========================================" << endl;
              cout << endl;

              int array[MAX_ROWS][MAX_COLS];
              int rows, cols;

              cout << "Masukkan jumlah baris array: ";
              cin >> rows;
              cout << "Masukkan jumlah kolom array: ";
              cin >> cols;

              cout << "Masukkan elemen-elemen array: " << endl;
              for (int i = 0; i < rows; i++) {
                for (int j = 0; j < cols; j++) {
                  cin >> array[i][j];
                }
              }

              cout << "Bilangan yang habis dibagi 3, 5, dan 7: " << endl;
              for (int i = 0; i < rows; i++) {
                for (int j = 0; j < cols; j++) {
                  if (array[i][j] % 3 == 0 && array[i][j] % 5 == 0 && array[i][j] % 7 == 0) {
                    cout << array[i][j] << " ";
                  }
                }
              }

              return 0;
            }

## Output

![2](https://user-images.githubusercontent.com/118744973/208370464-1457f264-eb36-4243-be03-fb5ca3954bac.JPG)

![2412](https://user-images.githubusercontent.com/118744973/208374554-122df0b3-9164-4ea5-bdaf-08dd4312ac58.JPG)
