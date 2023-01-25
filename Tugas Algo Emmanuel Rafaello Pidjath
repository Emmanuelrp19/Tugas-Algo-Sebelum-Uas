/*
Royhan Nabili Munthe 2270064516077
David Arrown 227064516097
Rafly Marfiano 227064516095
Emmmanuel Rafaello Pidjath 227064516071
Erlangga Aditya Hermawan 227064516062

*/
#include <iostream>
using namespace std;

int main(){
  
  int jumlah,jumlahbarang,biaya,kembalian;
  int total=0,total1=0,total2=0,total3=0,total4=0,totalsemua=0;
  int barang1,barang2,barang3,barang4,barang5,kode1;
  char kode,ulang;
  string menu,nama,nama1,nama2,nama3,nama4;
  string barang[6]= {"tidak","baju","celana","sepatu","hoodie","kemeja"};
  int harga[6]={0,50000,65000,200000,150000,100000};
  int *point_harga,*point_harga1,*point_harga2,*point_harga3,*point_harga4;
  string *point_nama,*point_nama1,*point_nama2,*point_nama3,*point_nama4;
  
  do{
  
  cout << "$$$$$ BANG RAFLY STORE $$$$$" << endl;
  cout << "=============================" << endl;
  cout << endl;
  
  cout << "Pilihan Menu : " << endl;
  cout << "1. Pricelist" << endl;
  cout << "2. Harga Barang" << endl;
  cout << "3. Mulai Order" << endl;
  cout << "4. Bayar" << endl;
  cout << "5. Cetak Receipt" << endl;
  cout << "Inputkan menu : ";
  cin >> kode;
  
  
  switch (kode) {
    case '1':;
    cout << "------------------------------" << endl;
    cout << "PRICELIST BANG RAFLY STORE" << endl;
    cout << "1. Baju      :Rp. 50000" << endl;
    cout << "2. Celana    :Rp. 65000" << endl;
    cout << "3. Sepatu    :Rp. 200000" << endl;
    cout << "4. Hoodie    :Rp. 150000" << endl;
    cout << "5. Kemeja    :Rp. 100000" << endl;
    break;
    case '2':;
    cout << "Masukan barang yang dicari (Semua huruf kecil) : ";
    cin >> menu;
    if (menu=="baju"){
      cout << "Harga barang : " << 50000 << endl;
    }
    else if (menu=="celana"){
    cout << "Harga barang : " << 65000 << endl;
  }
    else if (menu=="sepatu"){
      cout << "Harga barang : " << 200000 << endl;
    }
    else if (menu=="hoodie"){
      cout << "Harga barang : " << 150000 << endl; 
    }
    else if (menu=="kemeja") {
      cout << "Harga barang : " << 100000 << endl;
    }
    else {
      cout << "Barang yang anda cari tidak ditemukan !" << endl;
    }  
    break;
    
    case '3':;
    cout << "------------------------------" << endl;
    cout << "BARANG JUALAN BANG RAFLY STORE" << endl;
    cout << "1. Baju    " << endl;
    cout << "2. Celana  " << endl;
    cout << "3. Sepatu  " << endl;
    cout << "4. Hoodie  " << endl;
    cout << "5. Kemeja  " << endl;
    cout << "Berapa jenis barang yang ingin kamu beli : ";
    
     cin >> jumlah;
     if (jumlah == 0){
       cout << "Jenis barang tidak boleh 0" << endl;
   }
   else {
   
     for (int i=1;i<=jumlah;i++){                 
      cout << "input kode barang : ";
      cin >> kode1; 
     if(i==1){
       cout << "Masukkan jumlah barang : ";
       cin >> barang1;
       total = barang1*harga[kode1]; 
       point_harga=&harga[kode1];
       point_nama=&nama;
       nama = barang[kode1];
     }
     else if(i==2){
       cout << "Masukkan jumlah barang :";
       cin >> barang2;
       total1 = barang2*harga[kode1];
	   point_harga1=&harga[kode1];
	   point_nama1=&nama1;
       nama1 = barang[kode1];
     }
     else if(i==3){
       cout << "Masukkan jumlah barang :";
       cin >> barang3;
       total2 = barang3*harga[kode1];
	   point_harga2=&harga[kode1];
	   point_nama2=&nama2;
       nama2 = barang[kode1]; 
     }
     else if(i==4){
       cout << "Masukkan jumlah barang : ";
       cin >> barang4;
       total3 = barang4*harga[kode1];
	   point_harga3=&harga[kode1];
	   point_nama3=&nama3;
       nama3 = barang[kode1]; 
     }
     else if(i==5){
       cout << "Masukkan jumlah barang : ";
       cin >> barang5;
       total4 = barang5*harga[kode1];
	   point_harga4=&harga[kode1];
	   point_nama4=&nama4;
       nama4 = barang[kode1]; 
     }}
     
     totalsemua=total1+total2+total3+total4+total;
     cout << "Total yang dibayar : " << totalsemua <<endl;
 }
 	break;
 	
    case '4':;
    if (totalsemua>0){
	cout << "Total yang dibayar : " << totalsemua << endl;
    cout << "Masukan jumlah pembayaran : ";
    cin >> biaya;
    kembalian = biaya - totalsemua;
    if (biaya>totalsemua){
 		cout << "Kembalian anda = " << kembalian << endl;
 		cout << "====================" << endl;
  		cout << "Pembayaran Berhasil " << endl;
  		cout << "Silakan cetak receipt pada menu cetak " << endl;
  		cout << "====================" << endl;
    }
    else if(biaya<totalsemua){
      	cout << "Uang anda tidak cukup" << endl;
    }
    else {
    	cout << "--------------------" << endl;
    	cout << "Pembayaran Berhasil " << endl;
  		cout << "Silakan cetak receipt pada menu cetak " << endl;
  		cout << endl;
	}
	}
	else {
		cout << "Lakukan pemesanan barang dahulu" << endl;
	}
	break;
	case '5':;
	if (totalsemua==0){
		cout << "Harap Melakukan Pembayaran Terlebih Dahulu " << endl;
	}
	else {
		cout << endl;
		cout << "$$$$$ BANG RAFLY STORE $$$$$" << endl;
		cout << "===============================================================" << endl;
		cout << " ************************** RECEIPT ***************************" << endl;
		cout << endl;	
	
		cout << "================================================================" << endl;
		cout << "Total Harga Yang Harus Dibayar : " << totalsemua << endl;
		cout << "Uang Yang Telah Dibayar : " << biaya << endl;
		cout << "Kembalian Anda : " << kembalian << endl; 
		cout << "=================================================================" << endl;
		cout << endl;
	
		cout << "No" << "|" << "Nama Barang" << "  | " <<  "Harga Barang/pcs" << "| " << "Jumlah" << " | " << "Total" << " | " << endl;
		cout << 1 << " | " << *point_nama  << "	| " << *point_harga  << "	| " << barang1 << "	|	" << total  << "	| " << endl;
		cout << 2 << " | " << *point_nama1 << "	| " << *point_harga1 << "	| " << barang2 << "	|	" << total1 << "	| " << endl;
		cout << 3 << " | " << *point_nama2 << "	| " << *point_harga2 << "	| " << barang3 << "	|	" << total2 << "	| " << endl;
		cout << 4 << " | " << *point_nama3 << "	| " << *point_harga3 << "	| " << barang4 << "	|	" << total3 << "	| " << endl;
		cout << 5 << " | " << *point_nama4 << "	| " << *point_harga4 << "	| " << barang5 << "	|	" << total4 << "	| " << endl;
}	
	break;   
}
    cout << "Ingin memilih menu lain ? (y/t) : ";
    cin >> ulang;
}
while(ulang != 't');{
  	cout << "Terima kasih" << endl;  
}

 return 0;
}
