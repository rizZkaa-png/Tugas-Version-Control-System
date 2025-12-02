# GAME TEBAK ANGKA SEDERHANA

### Tugas Dokumentasi Program - CWK
Selamat datang di **Tugas Dokumentasi Program**, repo ini berisi dokumentasi program oleh kelompok kami!

## Pendahuluan
Brain Digits adalah program sederhana yang dibuat untuk melatih logika. Program ini dibuat untuk  mengembangkan kreativitas, melatih kesabaran, serta kemampuan berpikir secara kritis dan sistematis.
Game Brain Digits ini merupakan game tebak angka menggunakan bahasa python dengan tampilan _Graphical User Interface_ (GUI). Menggunakan Tkinter dan Library Rich. Secara acak akan dipilih angka rahasia lalu pemain menebak angka rahasia dengan jumlah kesempatan terbatas.

## Fitur utama
* Tampilan *Antamuka GUI* yang interaktif menggunakan Tkinter
* Menggunakan Library Rich untuk membuat pesan lebih berwarna
* Membuat angka rahasia secara otomatis
* Kesempatan yang diberikan *hanya 5 kali*
* Memberikan feedback kepada angka tebakan user
* Memunculkan *notifikasi* saat permainan berakhir
* Pemain bisa memulai ulang permainan setelah selesai

## Requirements
- [python](https://www.python.org/downloads/release/python-3140/) 
- tkinter
```bash
pip install tkinter
```
- rich
```bash
pip install rich
```

## Panduan Instalasi  
- Clone repo
```bash
git clone https://github.com/rizZkaa-png/Tugas-Version-Control-System.git
```
- Masuk ke folder proyek
```bash
 cd Tugas-Version-Control-System
```
## Panduan menjalankan
```bash
python 'Tebak angka.py'
```

## Dokumentasi teknis
<img width="751" height="671" alt="Image" src="https://github.com/user-attachments/assets/90559df8-6aa8-4acc-8c0f-80fec4d4887f" />


Penjelasan :  
Game tebak angka bekerja berdasarkan alur yang ditampilkan pada flowchart di atas. Saat permainan dimulai, sistem terlebih dahulu menentukan angka rahasia secara acak. Pemain diminta memasukkan angka tebakan pertama.
1. Pemain memasukkan tebakan
Sistem mengecek apakah tebakan tersebut benar.
2. Jika tebakan benar → tampilkan “Anda Menang”
Permainan langsung berakhir.
3. Jika tebakan salah → kesempatan dikurangi 1
Setelah itu, sistem mengecek kembali apakah kesempatan masih tersisa.
4. Jika masih ada kesempatan
Pemain dapat melakukan tebakan berikutnya, dan proses kembali ke langkah awal.
5. Jika kesempatan habis → tampilkan “Anda Kalah”
Permainan berakhir.
Dengan demikian, permainan akan terus berulang sampai pemain berhasil menebak angka dengan benar, atau kehabisan kesempatan.

## Daftar Kontributor :

| Nama Kontributor | NIM | Link Akun |
|-----------------------|-------|----|
| Preysli Candy Injili Makalew | 250211060026 | ([PreysliMakalew](https://github.com/PreysliMakalew)) |
| Sharen Charity Tampilang | 250211060074 | ([sharen121233](https://github.com/sharen121233)) |
| Rizka Az Zahra Rotty (Maintainer) | 250211060124 | ([rizZkaa-png](https://github.com/rizZkaa-png))|

## Lisensi
Repo ini dibuat untuk pemenuhan tugas pengenalan pemrograman topik 7 : Tugas dokumentasi kode
