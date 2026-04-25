# rauh. — Personal Portfolio

Single-page portfolio dengan desain dark minimalist, efek glassmorphism, dan beberapa sentuhan interaktif.
Live: https://hojiez.github.io/porto/

---

## Fitur Utama

- **Particle background** — animasi partikel (dot & cross) yang bergerak secara dinamis di atas background
- **Random audio player** — memutar lagu secara acak saat halaman dimuat, lengkap dengan tombol toggle dan strip "now playing"
- **Background GIF** — GIF animasi sebagai layer background dengan efek grayscale dan dimming otomatis
- **Glassmorphism UI** — card transparan dengan efek blur, border subtle, dan shadow berlapis
- **Responsive** — layout menyesuaikan ukuran layar

---

## Tech Stack

| Layer | Teknologi |
|---|---|
| Markup | HTML5 |
| Styling | Tailwind CSS (CDN) |
| Logic | Vanilla JavaScript |
| Font | Space Grotesk, DM Mono (Google Fonts) |

---

## How To Run

```bash
git clone https://github.com/Hojiez/porto.git
```

Buka file `index.html` langsung di browser. Tidak perlu install dependencies atau menjalankan server.

---

## Kustomisasi

Semua bagian yang perlu diubah sudah dikelompokkan di dalam blok **EDIT ZONE** di bagian atas `<script>`:

```js
const BG_GIF_URL = '...';   // URL GIF background
const AUDIO_TRACKS = [...]; // Daftar lagu (url + title)
```

Untuk mengubah konten (bio, proyek, link sosial) — cukup edit langsung di bagian HTML yang bersangkutan.

---

## Lisensi

Free to use sebagai referensi atau template. credits not needed, but appreciated.
