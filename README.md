# Emulator Bypass Patch Database for GODMODE

Repository ini digunakan oleh **GODMODE Engine** pada script cheat Free Fire.

## Struktur File

| File | Fungsi |
|------|--------|
| `signatures_OB53.json` | Patch signatures untuk game versi OB53 |
| `version.json` | Informasi versi terbaru |

## Cara Update

1. Buat file `signatures_OB54.json` untuk versi baru
2. Update `version.json` dengan versi terbaru
3. Commit ke GitHub

## Format Signature

```json
{
  "Name": "Nama Signature",
  "Pattern": "FF FF ?? FF ...",
  "HeadOffset": 240,
  "ChestOffset": 772,
  "Version": "OB53",
  "Verified": true,
  "CreatedAt": "2026-05-26T00:00:00Z"
}
