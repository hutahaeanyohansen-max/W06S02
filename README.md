# Sayur Mayur si Tegar

Praktikum PAM W6S2S3 - Navigation and Page Detail (Flutter).

## Struktur

```
lib/
  main.dart
  home.dart
  model/sayur_mayur.dart
  screen/sayur_page.dart
  screen/sayur_detail.dart
  widget/navbar_widget.dart
```

## Persiapan sebelum dijalankan

1. Buat project: `flutter create flutter_application_sayurmayur`, lalu timpa folder `lib/` dan `pubspec.yaml` dengan isi project ini.
2. Buat folder `assets/` dan isi dengan gambar `box1.jpg`, `box2.jpg`, `box3.jpeg`, `box4.jpg`, `box5.jpg`, `box6.jpg` (bayam, cabai, kentang, sawi, terong, tomat). Perhatikan ekstensi: box3 adalah `.jpeg`.
3. Font Varela: unduh `VarelaRound-Regular.ttf` dari Google Fonts, taruh di `fonts/`. Jika tidak mau memakai font, hapus bagian `fonts:` di `pubspec.yaml`.
4. Jalankan `flutter pub get`, lalu `flutter run`.

## Catatan

- Nomor WhatsApp di `sayur_detail.dart` (`628123456789`) adalah contoh; ganti sesuai kebutuhan.
- Untuk Android 11+, tambahkan di `android/app/src/main/AndroidManifest.xml` (di dalam `<manifest>`):

```xml
<queries>
  <package android:name="com.whatsapp" />
</queries>
```
