# bcfolks-staff

Halaman ini = aplikasi HP staff BC-Folks, dibuka di https://sicillia1109.github.io/bcfolks-staff/.

- **Sumber utama ada di repo `sicillia1109/BCFolks-Automation`** → `apps-script/Index.html`. Baca `AGENTS.md` di repo itu dulu (aturan pemilik + alur kerja).
- `index.html` di sini harus **sama persis** dengan `apps-script/Index.html`. Jangan edit di sini saja; ubah di BCFolks-Automation lalu salin.
- Halaman memanggil backend Apps Script lewat `doPost` ke `API_URL` (/exec). Salin `index.html` versi baru **hanya setelah** backend versi yang sama dirilis (Deploy → Manage deployments → New version), dan hanya dengan OK pemilik.
- Jangan pernah menaruh PIN, token, atau kredensial di repo ini (repo publik).
