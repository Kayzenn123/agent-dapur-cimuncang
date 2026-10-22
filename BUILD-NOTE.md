# BUILD-NOTE — demos/dapur-cimuncang/

## Sumber data (riset publik research/kuliner-rm-full.md — tidak dikarang)
- Nama: RM. Dapur Cimuncang — RM keluarga, masakan Sunda/Nusantara, saung + area bermain anak
- Alamat: Jl. Tentara Pelajar No.116 B, Babatan, Kec. Kadugede, Kab. Kuningan 45561
- Kontak: 08995858200 (ditampilkan 0899-5858-200; link wa.me/628995858200) — publik dari 2 artikel kuliner independen
- Jam: setiap hari 10.00–18.00
- Menu: Ayam Bakar Kampung (favorit, terverifikasi) + "aneka menu Nusantara lainnya"; harga spesifik **[ISI MANUAL]** → "Tanya via WhatsApp" (R7: tidak mengarang harga)
- Fasilitas: saung-saung, wahana bermain anak (ayunan, perosotan), cocok acara/jamuan keluarga & kantor
- IG/TikTok resmi: tidak ditemukan; website resmi: TIDAK ADA (hanya listing artikel + Google Maps)
- Maps: https://www.google.com/maps/search/?api=1&query=Dapur+Cimuncang+Kadugede+Kuningan

## Yang TIDAK dimasukkan (kepatuhan aturan)
- R8: tidak ada testimoni/ulasan/rating karangan di mana pun. Footer jujur: "Contoh website dibuat oleh Zenn — web designer Kuningan" + "Halaman ini contoh penawaran desain, bukan situs resmi RM Dapur Cimuncang."
- R7: harga & daftar menu lengkap tidak dikarang → "Tanya via WhatsApp" + note "Harga dapat berubah sewaktu-waktu".
- Fasilitas (saung, ayunan, perosotan, cocok acara) semua dari sumber publik; copy deskriptif generik ("adem", "betah") adalah copy produk, bukan klaim faktual bisnis.

## Teknis
- Satu file `index.html` (8.316 bytes), 100% self-contained.
- Nol request eksternal: font = system stack, gambar = emoji + gradasi CSS, tanpa `<img>`, tanpa font/CDN/JS eksternal.
- Satu-satunya URL luar adalah link klik-aksi (wa.me, tel:, google.com/maps) — tidak di-load otomatis.
- Mobile-first: max-width 640px, sticky header + sticky CTA WA/telepon di bawah, CTA di atas fold (hero).
- Struktur: header → hero (tagline + 2 tombol di atas fold + badge alamat/jam) → tentang → menu favorit → fasilitas → info praktis → CTA reservasi → footer.

## Self-review (RUBRIK.md, putaran 1 — 2026-10-22)
1. aktif-tanpa-web: 9 — bisnis aktif (disebut di ≥2 artikel kuliner independen), website resmi tidak ada, hanya listing pihak ketiga.
2. data: 9 — nama, alamat lengkap, jam, kontak, menu unggulan, fasilitas semua dari sumber publik terverifikasi; [ISI MANUAL] jujur untuk harga/menu lengkap/rating.
3. maps-wa: 8 — nomor dari 2 artikel publik independen, bukan data pribadi; link Maps ke pencarian nama (bukan koordinat karangan).
4. katalog: 9 — hanya menampilkan menu terverifikasi (Ayam Bakar Kampung favorit) + kategori generik "aneka menu Nusantara"; harga tidak dikarang; nol klaim palsu (R8).
5. paket: 8 — RM keluarga aktif tanpa web; paket Bisnis Rp1,2jt masuk akal (demo lengkap: menu, fasilitas, reservasi WA).
6. draft: 9 — 4 kalimat, personal, sebut masalah spesifik (belum punya website; Ayam Bakar Kampung favoritnya tidak terlihat online), tidak spam.
Rata-rata 8,7. SEMUA ≥8 → LOLOS putaran 1, tidak perlu revisi.
