#include <iostream>

using namespace std;

int main()
{
    int diskon, akhir, umur, tanggal;

    cout << "Harga Barang    = 9.800.000 " << endl << endl;
    cout << "Isi data dibawah ini untuk mendapat diskon" << endl << endl;

    cout << "Umur          = ";
    cin >> umur;

    cout << "Tanggal lahir = ";
    cin >> tanggal;

    while (tanggal>32 || tanggal<=0)
    {
        cout << endl << "Silahkan Masukkan Ulang" << endl <<endl;
        cout << "Tanggal lahir = ";
        cin >> tanggal;
    }
    cout << endl << endl;

    diskon = 9800000-(9800000*umur/100);
    akhir = diskon-(diskon*tanggal/100);

    cout <<"Harga Akhir      = " << akhir << endl;

return 0;
}
