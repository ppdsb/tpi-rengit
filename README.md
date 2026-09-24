# Rumah Teres Rengit — Landing Page

Landing page kutipan minat (lead capture) untuk projek **Rumah Teres 2 Tingkat, Taman Perbadanan Islam (TPI), Rengit** — projek RMMJ-D (Rumah Mampu Milik Johor) di bawah PIJ Property Development.

## Kandungan Repo

| Fail | Kegunaan |
|---|---|
| `index.html` | Laman utama (self-contained — semua CSS/JS terus dalam fail ini) |
| `house-front.jpg` | Gambar sebenar unit siap di tapak |
| `map-satellite.jpg` | Peta lokasi (satellite) |
| `logo.png` | Logo PIJ Property |

## Fungsi Laman

- Paparan maklumat projek: harga (RM300,000–RM350,000), spesifikasi unit, status CCC, dan lokasi (bersebelahan Sekolah Agama Merlong)
- Borang kutipan minat — apabila dihantar, mesej terus dibuka di **WhatsApp** (tiada pangkalan data/server backend)
- Pautan rasmi ke portal pendaftaran **PKPJ** (Perbadanan Kemajuan Perumahan Negeri Johor)
- Reka bentuk responsif (mudah alih & desktop), sokong mod terang & gelap

## ⚠️ Sebelum Digunakan Secara Live

Nombor WhatsApp disetkan dalam `index.html` (pembolehubah `WA_NUMBER`, dekat penghujung fail) — **wajib ditukar** kepada nombor rasmi Jualan & Pemasaran sebelum pautan ini dikongsi kepada orang awam. Nombor semasa adalah nombor testing.

Borang WhatsApp ini **bukan** permohonan rasmi rumah mampu milik — ia hanya untuk kutipan minat awal. Permohonan rasmi tetap melalui portal PKPJ.

## Hosting (GitHub Pages)

1. Pergi ke **Settings → Pages**
2. Di bawah **Build and deployment → Source**, pilih **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)** → Save
4. Laman akan live dalam beberapa minit di:
   `https://ppdsb.github.io/tpi-rengit/`

## Milik

PIJ Property Development
