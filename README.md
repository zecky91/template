# Landing Page SMK Negeri 1 Bukittinggi

Landing page resmi SMK Negeri 1 Bukittinggi dengan **hero section 3D animasi**, seluruh HTML/CSS/JS dalam **satu file** (`index.html`).

## Fitur yang Sudah Selesai
- **Hero 3D animasi** — latar Three.js (WebGL) dengan bentuk geometris melayang berwarna merah/kuning/putih (warna logo), partikel, torus knot, dan kamera parallax mengikuti mouse.
- **Logo 3D interaktif** — logo resmi (latar transparan) di panggung CSS 3D (`preserve-3d`) dengan tilt mengikuti kursor, cincin orbit berputar, glow bernapas, dan kartu badge melayang.
- Navbar tetap (blur saat scroll) + menu hamburger di mobile.
- Statistik animasi counter, ticker program keahlian, reveal-on-scroll.
- Seksi: Profil (visi/misi/kemitraan), Program Keahlian (6 kartu 3D hover), Keunggulan, CTA PPDB, Footer kontak.
- Responsif penuh (desktop, tablet, mobile) & menghormati `prefers-reduced-motion`.

## Struktur File
```
index.html               # seluruh halaman (HTML + CSS + JS inline)
images/logo.png          # logo resmi, latar transparan (dipakai di situs)
images/logo-original.png # file unggahan asli (latar putih)
README.md
```

## Entry URI
| Path | Keterangan |
|------|-----------|
| `index.html` | Halaman utama |
| `#hero-section`, `#about-section`, `#programs-section`, `#features-section`, `#cta-section`, `#site-footer` | Anchor navigasi |

## Library (CDN)
- Three.js 0.160 (jsDelivr) — animasi 3D
- Font Awesome 6.4 — ikon
- Google Fonts: Sora, Plus Jakarta Sans

## Belum Diimplementasikan
- Halaman detail tiap program keahlian, berita/pengumuman, galeri.
- Formulir PPDB online (bisa memakai RESTful Table API).
- Data nyata: nomor telepon, alamat lengkap, tautan media sosial, angka statistik (saat ini placeholder).

## Rekomendasi Langkah Selanjutnya
1. Ganti data placeholder (kontak, statistik, WhatsApp) dengan data resmi sekolah.
2. Tambahkan seksi berita/agenda menggunakan tabel data.
3. Tambahkan galeri foto kegiatan dan testimoni alumni.
4. Publikasikan melalui tab **Publish**.

## Penyimpanan Data
Tidak ada tabel data yang digunakan saat ini (halaman statis murni).
