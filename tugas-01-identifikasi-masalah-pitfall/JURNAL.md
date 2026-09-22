# Jurnal Proses — Tugas 1

> Isi jurnal ini selama proses diskusi berlangsung, bukan ditulis ulang rapi di akhir. Tulis dengan gaya bebas — poin diskusi, kebuntuan, perubahan pikiran.

## 22 September 2026
- **Peserta:** Naufal Fudhail, Diandra Naditya Mulkis, Samuel Nelson Wabiser
- **Poin diskusi:** 
  - Membedah masalah FoodGo dari studi kasus.
  - Sepakat mengambil 3 pitfall utama: *network reliability*, tidak ada *timeout* (*latency is zero*), dan kelemahan arsitektur monolitik (*single point of failure*).
  - Membagi tugas penulisan masing-masing pitfall ke tiap anggota.
- **Perbedaan pendapat (jika ada):** Awalnya sempat bingung membedakan antara masalah *latency is zero* dan *network is reliable*. Akhirnya disepakati kalau *network reliable* fokus ke perlunya *retry*, sedangkan *latency is zero* fokus ke pentingnya *timeout*.

## Review Silang
- Diandra mengomentari analisis Naufal: Penjelasan *cascading failure* di bagian *trade-off* sudah sangat jelas dan relevan dengan kasus FoodGo.
- Naufal mengomentari analisis Nelson: Usulan solusi migrasi ke *microservices* mungkin perlu diberi catatan bahwa praktiknya butuh waktu dan *effort* besar untuk tim kecil.

## Log Penggunaan AI (Level 2)

> Wajib diisi sesuai kebijakan Level 2 di `../RUBRIK-UMUM.md`. Tulis "Tidak memakai AI" pada baris pertama jika memang tidak dipakai. Hanya untuk brainstorming ide/outline — bukan untuk kode/analisis/teks akhir.

| Tanggal | Tool AI | Prompt yang diberikan | Ringkasan saran/ide AI | Bagaimana diolah jadi tulisan/kode sendiri |
|---|---|---|---|---|
| 22 September 2026 | Gemini | Meminta bantuan brainstorming 3 pitfall dan struktur kerangka jawaban untuk studi kasus FoodGo. | AI memberikan penjabaran untuk asumsi "network is reliable", "latency is zero", dan "single point of failure", beserta ide solusi (exponential backoff, circuit breaker, microservices) dan trade-off-nya. | Tim menyusun ulang argumen AI dengan gaya bahasa sendiri, memotong bagian yang tidak perlu, menghubungkan penjelasan secara spesifik dengan gejala di skenario FoodGo, dan membagi tugas penulisan akhir ke tiap anggota. |
