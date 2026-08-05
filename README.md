# 🔐 Password Security Toolkit

Tools sederhana untuk mengecek kekuatan password dan mendeteksi apakah password pernah bocor di data breach.

## 🔧 Fitur

- ✅ Cek panjang password
- ✅ Cek kombinasi huruf besar, kecil, angka, simbol
- ✅ Deteksi pola umum (123, abc, qwerty, admin)
- ✅ Skor 0-100 + rating (Lemah/Cukup/Kuat)
- ✅ Cek kebocoran via API Have I Been Pwned
- ✅ Saran perbaikan

## 📝 Penggunaan

```bash
python pwd_checker.py
Atau langsung kasih argumen:

bash
python pwd_checker.py admin123

📊 Contoh Output
📊 Skor: 35/100 - ❌ LEMAH BANGET!

📝 Detail Penilaian:
   ❌ Password terlalu pendek (8 karakter)
   ❌ Tambahin huruf besar (A-Z)
   ✅ Ada huruf kecil
   ✅ Ada angka
   ❌ Tambahin simbol
   ⚠️ Password mengandung pola umum

🚨 PERINGATAN! Password ini pernah bocor!

📦 Instalasi
git clone https://github.com/FoxShadow32/password-security-toolkit.git
cd password-security-toolkit
pip install -r requirements.txt
python pwd_checker.py

📜 Lisensi
MIT License
Dibuat oleh FoxShadow32


---

