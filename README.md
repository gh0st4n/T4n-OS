# T4n OS

T4n OS adalah distribusi Linux berbasis Void Linux yang dirancang untuk pengguna yang mengutamakan kinerja, kesederhanaan, fleksibilitas, serta kemampuan kustomisasi maksimum. Filosofinya berfokus pada kebebasan penuh pengguna untuk mengontrol sistem, tanpa mengorbankan stabilitas maupun performa.

---

## Fitur Utama

### 1. **VUR (Void User Repo)**

Repositori komunitas yang memungkinkan pengguna untuk berbagi, membangun, dan mendistribusikan paket di luar repositori resmi Void Linux. Paket-paket dalam VUR dapat berupa:

* Tool pentesting
* Software eksperimen
* Build khusus optimasi CPU
* Patches custom kernel / GUI / DE

### 2. **T4n-Manpy (VUR Helper)**

CLI helper/tool yang mempermudah pengguna dalam:

* Menginstall paket dari VUR
* Mengupdate paket berbasis template
* Membangun paket otomatis dari source
* Menangani dependency build

Contoh penggunaan:

```bash
t4n-manpy install <paket>
t4n-manpy build <paket>
t4n-manpy submit <paket>
```

---

## Antarmuka Sistem

### **GUI Mode**

```
X11      : XFCE / BSPWM
Wayland  : COSMIC DE & RiverWM (atau WM buatan sendiri berbasis wlroots - Zig)
```

T4n OS memberikan kebebasan kepada pengguna untuk memilih lingkungan grafis sesuai kebutuhan: ringan, produktif, atau modern.

### **CLI Mode**

Bagi pengguna yang menginginkan pengalaman minimalis dan efisien, T4n OS tetap dapat dijalankan tanpa GUI. Cocok untuk:

* Server
* Pengembangan low-level
* Penggunaan resource minimal

---

## Skema Rilis Versi

T4n OS menyediakan dua tipe model rilis:

### **Rolling Release**

* Sistem selalu up-to-date
* Cocok untuk pengguna berpengalaman atau yang ingin latest stack

### **Semi-Rolling Release** (Direkomendasikan-Server)

### Flavor sesuai kebutuhan pengguna:

| Edition   | Tujuan Penggunaan            | Keterangan                                                       |
| --------- | ---------------------------- | ---------------------------------------------------------------- |
| Developer | Programming, Pentest, DevOps | Toolchain lengkap, VM, container, compiler zig/python/rust/c dll |
| General   | Daily Use, Multimedia, Web   | Ringan, aman, stabil                                             |
| Gamer     | Game Linux & Proton          | Optimasi Kernel, Mesa & Vulkan, Wine/Proton siap pakai           |
| Office    | Produktivitas Kantor         | LibreOffice, PDF, Font, Integrasi printer                        |

---

## Filosofi Sistem

* **Kebebasan Tinggi**: Tidak memaksa user mengikuti struktur tertentu.
* **Kustomisasi Maksimal**: Semua layer sistem dapat dibentuk ulang.
* **Stabil & Minimal**: Tanpa bloat, tanpa sistem init raksasa.
* **Untuk Pengguna Kreatif**: Memberi ruang eksplorasi, bukan membatasi.

---

## Status Pengembangan

Proyek dalam tahap pengembangan aktif. Kontribusi, testing, dan saran sangat diterima.

---

## Lisensi

T4n OS mengikuti lisensi Void Linux dan paket-paket terkait. Lisensi tambahan akan dicantumkan pada modul mandiri.

---

## Kontak / Komunitas

Akan diumumkan setelah rilis tahap awal.

---

**T4n OS — Untuk yang ingin menguasai sistem, bukan sekadar memakainya.**
