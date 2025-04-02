# jawa-icons
Jawa Icon Theme adalah sebuah tema ikon bertema budaya Jawa untuk lingkungan desktop Linux. Tema ini dirancang dengan gaya minimalis menggunakan format SVG, dengan warna dan desain yang mencerminkan estetika khas budaya Jawa.

## Warna Khas Jawa
- Hitam & Emas → Terinspirasi dari batik klasik dan ukiran Jepara.
- Coklat & Krem → Warna tanah dan kayu, sering ditemukan dalam wayang dan batik.
- Merah Bata → Simbol dari bangunan tradisional seperti candi dan joglo.
- Hijau Tua → Terinspirasi dari filosofi alam dan keharmonisan.

    ### Palet Warna

    | Warna | Kode Hex |
    |-------|---------|
    | **Coklat Kayu** | `#8D5524` | 
     | **Krem Muda** | `#F2ECE4` | 
    | **Emas Klasik** | `#FFD700` |
    | **Merah Bata** | `#E63946` | 
    | **Hitam Elegan** | `#4A4A4A` | 
    | **Hijau Alami** | `#A8C686` |

## Fitur
- **Desain Minimalis**: Ikon dibuat sederhana namun tetap mencerminkan budaya Jawa.
- **Format SVG**: Mendukung resolusi tinggi tanpa kehilangan kualitas.
- **Palet Warna Khas Jawa**: Menggunakan warna-warna yang terinspirasi dari batik, ukiran kayu, dan elemen budaya lainnya.
- **Kompatibel dengan GTK & KDE**: Bisa digunakan di berbagai desktop environment seperti GNOME, KDE, XFCE, dll.

## Struktur Folder
```
JawaIconTheme/
├── index.theme
├── scalable/
│   ├── apps/
│   │   ├── terminal.svg
│   │   ├── file-manager.svg
│   │   ├── browser.svg
│   ├── places/
│   │   ├── home.svg
│   │   ├── folder.svg
│   ├── devices/
│   │   ├── computer.svg
│   │   ├── printer.svg
```

## Instalasi
1. **Salin Tema Ikon**
   ```sh
   mkdir -p ~/.icons
   cp -r JawaIconTheme ~/.icons/
   ```
   atau untuk sistem-wide:
   ```sh
   sudo cp -r JawaIconTheme /usr/share/icons/
   ```

2. **Perbarui Cache Ikon**
   ```sh
   gtk-update-icon-cache -f ~/.icons/JawaIconTheme
   ```

3. **Aktifkan Tema Ikon**
   - Untuk GNOME, gunakan **GNOME Tweaks** dan pilih **Jawa Icon Theme**.
   - Untuk KDE, ubah di **System Settings > Icons**.

## 🤝 Kontribusi
Kami membuka kontribusi dari komunitas!
- **Menambahkan Ikon Baru**: Kirimkan ikon dalam format SVG dengan gaya yang seragam.
- **Perbaikan & Optimalisasi**: Jika Anda menemukan kesalahan atau ikon yang bisa diperbaiki, silakan buat pull request.
- **Ide & Saran**: Jika Anda punya ide desain, silakan buat issue di repo ini.

### Cara Berkontribusi
1. **Fork repository**
2. **Buat branch baru**
3. **Tambahkan atau ubah ikon**
4. **Kirim pull request**

Terima kasih telah mendukung proyek ini! 🙌
