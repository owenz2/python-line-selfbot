# Selfbot

Ini cuma selfbot LINE biasa berbahasa python diclone dari repo [ini](https://github.com/Nadyatjia/BotLinePython3).

# Instalasi

Clone dahulu github ini dengan cara

```bash
git clone https://github.com/inidwiii/python-line-selfbot python-line-selfbot
```

Kemudian arahkan ke folder itu

```bash
cd python-line-selfbot
```

Untuk menginstall, pastikan kamu memiliki bahasa pemrograman python terinstall di devicemu.
Jika sudah ada, maka kamu bisa lanjut ke instruksi dibawah

- Pertama, install virtual environment pada folder ini agar program ini tidak menginstall dependencies
secara global.

```bash
python -m venv ./venv
```

- Kemudian kita aktifkan virtual environment yang telah kita buat

Khusus windows (cmd)

```bash 
cd venv/Scripts/ && activate
```

Selain (cmd)

```
venv/Scripts/activate
```

- Setelah selesai instruksi diatas, barulah anda menginstall dependencies yang terdaftar pada `requirements.txt`. Jalankan perintah dibawah ini untuk meng-update `pip` terlebih dahulu.

```bash
python -m pip install pip --upgrade
```

- Kemudian lanjutkan ke instalasi

```bash
pip install --no-cache-dir -r requirements.txt
```

- Lalu setup akun mu pada file `Nadyasb.py`

```python
nadya = LINE('email', 'password')
```

- Jika sudah menjalankan semua instruksi diatas, maka sudah bisa melanjutkan running instruksi dibawah ini

```bash
python Nadyasb.py
```

Kemudian jika diminta token maka masukan token, jika tidak tunggu hingga bot siap dijalankan.

Jika sudah selesai menggunakan bot, kamu bisa menekan tombol `ctrl` dan `c` untuk mengakhiri program. Lalu matikan virtual environment nya dengan cara ketik

```bash
deactivate
```