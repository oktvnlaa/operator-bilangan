# operator-bilangan
#include <iostream>
using namespace std;

int main(){
	double HargaSebuahPena;
	double HargaSebuahBuku;
	double HargaSebuahPenghapus;
	double HargaSebuahPenggaris;
	
	
	cin>>HargaSebuahPena;
	cin>>HargaSebuahBuku;
	cin>>HargaSebuahPenghapus;
	cin>>HargaSebuahPenggaris;
	
	cout<<endl;
	cout<<"Harga 5 Buah Pena 	= Rp."<<5*HargaSebuahPena<<endl;
	cout<<"Harga 2 Buah Buku 	= Rp."<<2*HargaSebuahBuku<<endl;
	cout<<"Harga 5 Buah Penghapus 	= Rp."<<5*HargaSebuahPenghapus<<endl;
	cout<<"Harga 2 Buah Penggaris 	= Rp."<<2*HargaSebuahPenggaris<<endl;
	
	return 0;
}
