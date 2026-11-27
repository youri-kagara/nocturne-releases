# Nocturne by Azreal

Pemutar musik untuk **Android, Windows, Linux, dan macOS**.

**[⬇️ Download versi terbaru](https://github.com/youri-kagara/nocturne-releases/releases/latest)**

Setelah terpasang, Nocturne **update sendiri**: saat ada versi baru, muncul jendela "Update tersedia" berisi daftar perubahan. Tinggal tekan **Update sekarang**.

---

## Cara pasang

### 📱 Android (8.0 ke atas)

1. Buka halaman [rilis terbaru](https://github.com/youri-kagara/nocturne-releases/releases/latest) dari HP, unduh **`Nocturne-<versi>.apk`**.
2. Buka file yang terunduh, lalu tekan **Pasang**.
3. Kalau diminta izin **"Instal aplikasi tidak dikenal"**, izinkan untuk browser atau File Manager yang dipakai (sekali saja).

Nocturne tidak ada di Play Store, jadi HP bisa memberi peringatan. Ini wajar:

| Muncul | Yang harus dilakukan |
|---|---|
| **Samsung: "Diblokir oleh Auto Blocker"** | Buka **Pengaturan → Keamanan dan privasi → Auto Blocker → Matikan**. Pasang atau update Nocturne, lalu nyalakan lagi kalau mau. Auto Blocker memblokir semua aplikasi dari luar Play Store/Galaxy Store, bukan khusus Nocturne. |
| **Google Play Protect: "Aplikasi tidak dikenal" / "Aplikasi tidak aman"** | Tekan **Detail lainnya → Tetap pasang**. Peringatan ini muncul untuk aplikasi yang belum pernah dipindai Google. |
| **Xiaomi/Redmi/POCO: pemindai keamanan** | Tunggu pemindaian selesai, lalu tekan **Lanjutkan / Tetap pasang**. |

Saat **update dari dalam aplikasi**, Android selalu meminta konfirmasi **Pasang**. Kalau update gagal di Samsung, matikan Auto Blocker sebentar seperti di atas, lalu tekan **Coba lagi**.

### 🪟 Windows 10/11

1. Unduh **`Nocturne-Setup-<versi>.exe`**, lalu jalankan.
2. Windows bisa menampilkan **"Windows protected your PC"** (SmartScreen), karena installer belum memakai sertifikat berbayar. Tekan **More info → Run anyway**. Cukup sekali; update berikutnya tidak memunculkan ini lagi.
3. Tidak perlu akses admin. Nocturne terpasang untuk akun Windows kamu saja, dengan shortcut di Start Menu.

> **Windows 11 dengan Smart App Control aktif:** aplikasi tanpa sertifikat diblokir total. Matikan di **Windows Security → App & browser control → Smart App Control**.
>
> `Nocturne-<versi>.msi` adalah installer yang sama; itu yang dipakai Nocturne untuk update otomatis. Untuk pemasangan pertama, pakai yang `.exe`.

### 🍎 macOS (Apple Silicon, M1 ke atas)

1. Unduh **`Nocturne-<versi>.dmg`**, buka, lalu seret **Nocturne** ke folder **Applications**.
2. Saat pertama dibuka, macOS bisa bilang aplikasi tidak bisa diverifikasi. Buka **System Settings → Privacy & Security**, gulir ke bawah, tekan **Open Anyway**. Atau klik kanan Nocturne di Applications → **Open**.

Mac dengan chip Intel belum didukung.

### 🐧 Linux (x64)

- **Semua distro:** unduh **`Nocturne-<versi>-x86_64.AppImage`**, jadikan bisa dijalankan (`chmod +x Nocturne-*.AppImage`), lalu buka. Versi AppImage bisa update sendiri.
- **Debian/Ubuntu:** `sudo apt install ./Nocturne-<versi>.deb`. Versi `.deb` tidak bisa update sendiri; saat ada update, Nocturne membuka halaman ini untuk diunduh manual.

---

## Isi setiap rilis

| File | Untuk |
|---|---|
| `Nocturne-<versi>.apk` | Android |
| `Nocturne-Setup-<versi>.exe` | Windows, pemasangan pertama |
| `Nocturne-<versi>.msi` | Windows, dipakai updater di aplikasi |
| `Nocturne-<versi>.dmg` | macOS Apple Silicon |
| `Nocturne-<versi>-x86_64.AppImage`, `Nocturne-<versi>.deb` | Linux |
| `model_*.onnx` | Model Automix, diunduh otomatis oleh aplikasi |
| `source-<versi>.zip` | Kode sumber rilis tersebut |
| `latest.json` | Info update yang dibaca aplikasi |

## Lisensi

Nocturne adalah perangkat lunak bebas berlisensi **GPL-3.0**. Kode sumber lengkap tiap versi ada di `source-<versi>.zip` pada rilisnya, dan pemberitahuan hukum lengkap bisa dibuka dari **Settings → GPL-3.0** di aplikasi.
