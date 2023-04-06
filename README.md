# python

Tahapan pertama yang dilakukan adalah menginstall Python terlebih dahulu,
berikut langkah-langkah yang perlu dilakukan:
1. Download python pada link https://www.python.org/downloads/. Instalasi
Python tersedia pada OS windows, mac OS dan Linux. Silahkan download
installer sesuaikan dengan OS yang dimiliki
2. Setelah selesai download, klik dua kali pada installer. Berikut tampilan pada
mac os.
3. Untuk windows agar lebih memudahkan pencarian silahkan lakukan
customized untuk menentukan lokasi direktori instalasi. Sebaiknya instal
pada direktori C dan buat folder baru dengan nama ‘PythonXX’ (XX
menandakan versi python)
4. Ikuti perintah instalasi hingga akhir
5. Untuk pengguna windows, pastikan path sudah ditambahkan pada system
variabel
Kegiatan Praktikum 2: Instalasi Code Editor
Code editor yang digunakan adalah vs code, berikut tahapan untuk download.
1. Download installer vs code di https://code.visualstudio.com/download

3. Pada halaman download sesuaikan versi OS yang digunakan
4. Setelah selesai download, klik dua kali pada installer
5. Ikuti petunjuk instalasi sampai selesai
6. Setelah sukses terinstal, buka aplikasi vs code dan buka menu ‘Extensions’
pada sidebar kiri.
6. Pada kolom pencarian ketikkan kata kunci ‘Python’, extensions akan terlihat
pada gambar berikut

diinstal dan disetel dalam variabel lingkungan, mungkin perlu menentukan
bahasa Python untuk digunakan di terminal untuk menginstal library ke
lingkungan global.
Untuk membuat virtual environment gunakan perintah berikut:
# macOS/Linux
# You may need to run sudo apt-get install python3-venv first
python3 -m venv .venv
# Windows
# You can also use py -3 -m venv .venv
python -m venv .venv

# For Windows
.venv\scripts\activate
# For macOS/Linux
source .venv/bin/activate


pip install opencv-python
