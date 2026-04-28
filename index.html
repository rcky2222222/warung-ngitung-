#include <iostream>
#include <string>
using namespace std;

// =============================================
// STRUCT: menyimpan data satu produk
// =============================================
struct Produk {
    int    id;
    string nama;
    double harga;
    int    stok;
};

// =============================================
// VARIABEL GLOBAL
// Array untuk menyimpan banyak produk
// =============================================
Produk daftar[20];  // maksimal 20 produk
int jumlahProduk = 0;

// =============================================
// FUNGSI: Tambah produk
// =============================================
void tambahProduk() {
    if (jumlahProduk >= 20) {
        cout << "Produk sudah penuh!" << endl;
        return;
    }

    Produk p;
    p.id = jumlahProduk + 1;

    cin.ignore();
    cout << "Nama produk : "; getline(cin, p.nama);
    cout << "Harga       : "; cin >> p.harga;
    cout << "Stok        : "; cin >> p.stok;

    daftar[jumlahProduk] = p;
    jumlahProduk++;

    cout << ">> Produk berhasil ditambahkan!" << endl;
}

// =============================================
// FUNGSI: Tampilkan semua produk
// =============================================
void lihatProduk() {
    if (jumlahProduk == 0) {
        cout << "Belum ada produk." << endl;
        return;
    }

    cout << "------------------------------------" << endl;
    cout << "ID | Nama           | Harga  | Stok" << endl;
    cout << "------------------------------------" << endl;

    for (int i = 0; i < jumlahProduk; i++) {
        cout << daftar[i].id << "  | "
             << daftar[i].nama << "\t| "
             << daftar[i].harga << "\t| "
             << daftar[i].stok << endl;
    }

    cout << "------------------------------------" << endl;
}

// =============================================
// FUNGSI: Transaksi penjualan
// =============================================
void transaksi() {
    lihatProduk();

    int id, jumlahBeli;
    cout << "Pilih ID produk : "; cin >> id;
    cout << "Jumlah beli     : "; cin >> jumlahBeli;

    // Cari produk berdasarkan ID
    int idx = -1;
    for (int i = 0; i < jumlahProduk; i++) {
        if (daftar[i].id == id) {
            idx = i;
            break;
        }
    }

    // Validasi
    if (idx == -1) {
        cout << "Produk tidak ditemukan!" << endl;
        return;
    }
    if (jumlahBeli > daftar[idx].stok) {
        cout << "Stok tidak cukup! Stok tersisa: " << daftar[idx].stok << endl;
        return;
    }

    // Hitung total
    double total = daftar[idx].harga * jumlahBeli;
    cout << "Total bayar : Rp " << total << endl;

    double bayar;
    cout << "Uang bayar  : Rp "; cin >> bayar;

    if (bayar < total) {
        cout << "Uang kurang!" << endl;
        return;
    }

    cout << "Kembalian   : Rp " << bayar - total << endl;

    // Kurangi stok
    daftar[idx].stok -= jumlahBeli;

    cout << ">> Transaksi berhasil!" << endl;
}

// =============================================
// FUNGSI: Laporan sederhana
// =============================================
void laporan() {
    cout << "===== LAPORAN STOK =====" << endl;

    for (int i = 0; i < jumlahProduk; i++) {
        cout << daftar[i].nama << " - Sisa stok: " << daftar[i].stok;
        if (daftar[i].stok <= 3) cout << " (MENIPIS!)";
        cout << endl;
    }

    cout << "========================" << endl;
}

// =============================================
// MAIN: Menu utama program
// =============================================
int main() {
    int pilihan;

    do {
        cout << "\n====== WARUNG DIGITAL ======" << endl;
        cout << "1. Tambah Produk" << endl;
        cout << "2. Lihat Produk" << endl;
        cout << "3. Transaksi Penjualan" << endl;
        cout << "4. Laporan Stok" << endl;
        cout << "0. Keluar" << endl;
        cout << "Pilih: "; cin >> pilihan;

        switch (pilihan) {
            case 1: tambahProduk(); break;
            case 2: lihatProduk();  break;
            case 3: transaksi();    break;
            case 4: laporan();      break;
            case 0: cout << "Terima kasih!" << endl; break;
            default: cout << "Pilihan tidak valid." << endl;
        }

    } while (pilihan != 0);

    return 0;
}
