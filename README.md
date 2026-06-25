# Download DOCX via QR

Project statis ini siap di-deploy ke Vercel.

## File penting

- `index.html`: halaman untuk menampilkan QR dan tombol download.
- `download.html`: halaman perantara agar Safari/iPhone tetap punya tombol fallback.
- `surat-keterangan-toefl-ft-unmul.docx`: file yang akan diunduh saat QR discan.
- `vercel.json`: header agar file DOCX dikirim sebagai attachment/download.

## Cara deploy

1. Push folder ini ke GitHub.
2. Import repository ke Vercel.
3. Deploy tanpa build command khusus.
4. Buka domain Vercel hasil deploy.
5. Cetak atau screenshot QR dari halaman tersebut.

QR akan otomatis mengarah ke:

```text
https://domain-vercel-anda/download.html
```
