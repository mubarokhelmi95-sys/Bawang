# Animasi Bawang (GIBRIG)

Taruh semua file di satu folder repo (root), lalu aktifkan GitHub Pages:
Settings → Pages → Deploy from a branch → `main` / `(root)`.

File yang dipakai `index.html`:
- GIBRIG_WOMAN_HIJAB_HUMANOID.glb, GIBRIG_MAN_CURLY_HUMANOID.glb, GIBRIG_BOY_ORANGE_HUMANOID.glb
- bawang_mix.mp3 (narasi + efek suara + musik). Kalau tidak ada, otomatis pakai bawang.wav (narasi saja)

Tombol: ▶ putar, geser untuk lompat waktu, slider kecil = kecerahan, ⏺ Rekam = unduh video .webm (pakai Chrome/Edge).
Resolusi: tambahkan `?q=1920` di URL untuk 1080x1920 (butuh GPU kuat), default 720x1280.
Tidak bisa dibuka lewat file:// karena browser memblokir pemuatan .glb; pakai GitHub Pages atau `python3 -m http.server`.
