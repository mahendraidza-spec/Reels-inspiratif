# Naskah Episode 5 — Rabu 18 Nov 2026 (Colab saja — klip terbaik dari tiap alat)

> **NASKAH — ditulis 17 Nov ~19:15 WIB, malam sebelum produksi.** Cerita diputuskan Idza 16 Nov: episode 5 memakai cerita Frans dari video rekomendasi user (https://www.facebook.com/share/v/1J8aTq5HJ1/, 63.953 likes). Episode 4 ("Sepatu Jebol Sebelum Ujian") tayang 17 Nov ~17:16 WIB, telat ~45 menit karena Wan2GP di Colab butuh hampir 2 jam untuk 7 adegan. **Keputusan Idza 17 Nov 20:33 WIB: produksi TETAP jam 15:00 (cron biasa), tidak dimajukan ke pagi — risiko telat lagi diterima.**
>
> **PERUBAHAN ALAT 18 Nov 10:59 WIB (perintah Idza): aturan "Colab saja" DICABUT. Boleh pakai Google Flow (Veo) lagi dan cari tools lain — yang penting video BAGUS. Alasan: Reels ep. 1–4 dinilai Idza patah-patah dan tidak jelas. Perbaikan wajib episode 5: gerakan harus mulus — pakai frame interpolation (RIFE) ke 30 fps untuk klip Wan2GP, dan/atau Veo untuk adegan yang gerakannya paling penting. Cek dulu hasil tontonan browser di profil (task browser a79b2f12) sebelum produksi bila sudah ada laporannya.**
>
> **MULAI LEBIH AWAL 18 Nov 11:05 WIB (perintah Idza "Ok kerjakan"): produksi episode 5 DIMULAI PAGI/SIANG ini, bukan menunggu cron 15:00. Target upload tetap 16:30 WIB. Cron 15:00 JANGAN memproduksi ulang — cek dulu apakah Reel episode 5 sudah tayang; kalau sudah, lewati saja.**
>
> **ALAT (perintah Idza 16 Nov 21:16 WIB: "Colab saja"):** produksi HANYA di Google Colab — buat klip dari setiap alat yang bisa jalan di Colab (Wan2GP dulu; kalau sempat coba HunyuanVideo-1.5 / LTX-Video), pilih klip TERBAIK per adegan, lalu rakit jadi satu video. Gambar dibedakan tiap alat. Kalau GPU Colab tidak dapat, laporkan ke Idza dulu — jangan otomatis ganti ke Flow.

- **Judul:** "Diancam Potong Gaji Gara-Gara Sholat"
- **Jadwal:** produksi jam 15:00 (cron biasa, sesuai keputusan Idza 17 Nov 20:33 WIB), upload 16:30 WIB ke profil pribadi (facebook.com/idzaa23), seperti biasa.
- **Durasi target:** 7 adegan × ±5 detik ≈ 35 detik, vertikal 9:16.
- **Aturan (perintah Idza 15 Nov 23:35 WIB): episode WAJIB ada dialog percakapan karakter utama, dari adegan awal sampai akhir — bukan cuma di akhir. Bentuk dialog: SUARA (TTS) — karakternya ngomong.** Suara: Frans = laki-laki muda (avocado_v2:MAI_03, nada tenang dan tegas), Pak Darma = laki-laki dewasa (MAI_03, nada lebih berat/tegas), Rina = perempuan (avocado_v2:MAI_01). TTS dibuat per adegan, dicampur di atas musik dengan musik lebih pelan; **tiap adegan dialognya MAKS ~70 karakter total supaya muat dalam ±5 detik.** **Watermark (perintah Idza 15 Nov 23:39 WIB): teks idza.mahendra tanpa tanda petik, di pojok kanan atas video, semi-transparan, terbaca tapi tidak menutupi adegan/wajah — dipasang saat assembly, BUKAN di dalam Wan 2.2.**
- **Edit MAKSIMAL (perintah Idza 15 Nov 23:34 WIB, biar FYP meledak): usahakan SEMUA 7 adegan dianimasikan selama kuota/GPU cukup; hook kuat di 3 detik pertama; konteks karakter + cerita jelas sejak adegan 1; musik emosional yang naik ke klimaks; tidak ada adegan mati; thumbnail clickbait wajib.**
- **Thumbnail clickbait (wajib):** frame adegan 1 (Pak Darma menunjuk Frans dengan wajah marah, Frans tenang) + teks besar "DIANCAM POTONG GAJI GARA-GARA SHOLAT!" + sub-teks "Ternyata Dia yang Selamatkan Perusahaan"

## Tokoh (BARU — beda dari Slamet, Pak Darno, Mas Budi, Pak Sastro, Dimas, dan Bu Ratna)

**Frans, 30 tahun, staf gudang.** Rambut hitam pendek rapi, kulit sawo matang, kemeja seragam gudang biru, celana hitam, sepatu safety, wajah tenang dan jujur. Wajah dan ciri ini dipakai SAMA PERSIS di semua prompt gambar adegan 1–7.

**Pak Darma, 48 tahun, manajer gudang.** Rambut hitam beruban, kemeja putih lengan panjang, celana kain hitam, wajah tegas lalu menyesal.

**Rina, 27 tahun, rekan kerja Frans di gudang.** Kerudung coklat muda, seragam gudang biru, wajah khawatir lalu lega.

## Cerita (gaya EL BORA TV: orang biasa berbuat baik → konflik → pertolongan datang → moral)

1. **Pagi di gudang.** Frans pamit sholat. Pak Darma marah dan mengancam memotong gajinya kalau tetap pergi sholat di jam kerja.
2. **Frans tetap sholat.** Dengan tenang Frans sholat di musala kecil gudang, lalu kembali bekerja seperti biasa.
3. **Frans memeriksa label kirim.** Saat mengecek tumpukan paket, Frans menemukan label pengiriman tertukar — alamat dan barangnya salah.
4. **Frans melapor.** Frans menunjukkan label yang salah itu kepada Pak Darma — kiriman besar itu hampir salah alamat.
5. **Pak Darma memeriksa.** Pak Darma mengecek sendiri dan sadar perusahaan hampir rugi besar kalau paket itu terkirim.
6. **Pak Darma minta maaf.** Pak Darma mengakui kesalahannya dan meminta maaf kepada Frans di depan Rina.
7. **Frans dipromosikan.** Frans dipanggil ke ruangan dan diangkat jadi Operational Manager — seragam baru, papan nama baru, rekan-rekan bertepuk tangan.

**Moral (teks di caption, bukan di video):** "Orang yang teguh pada prinsipnya tidak akan pernah rugi — ketelitian dan kejujuran selalu menemukan jalannya."

## Dialog percakapan per adegan (WAJIB — karakter ngomong dari adegan awal, bukan cuma di akhir; DIPENDEKKAN, maks ~70 karakter per adegan supaya muat ±5 detik)

1. Pak Darma: "Izin sholat? Gajimu saya potong!"
2. Frans: "Saya tetap sholat, Pak. Lima menit saja."
3. Frans: "Label ini tertukar... alamatnya salah!"
4. Frans: "Pak, kiriman ini hampir salah alamat."
5. Pak Darma: "Benar... perusahaan hampir rugi besar."
6. Pak Darma: "Maafkan saya, Frans. Kamu benar."
7. Pak Darma: "Mulai hari ini, kamu Operational Manager."

## Prompt gambar per adegan (karakter sama persis di semua adegan)

Ciri tokoh yang diulang verbatim di tiap prompt gambar: "Frans, 30 tahun, staf gudang Indonesia, rambut hitam pendek rapi, kemeja seragam gudang biru, celana hitam, sepatu safety" dan "Pak Darma, 48 tahun, manajer gudang Indonesia, rambut hitam beruban, kemeja putih lengan panjang".

1. Pagi di gudang besar, Pak Darma menunjuk Frans dengan wajah marah, Frans berdiri tenang memegang sajadah, rak-rak barang di belakang.
2. Frans sholat dengan khusyuk di musala kecil di sudut gudang, cahaya pagi masuk dari jendela, suasana tenang.
3. Frans jongkok memeriksa tumpukan paket kardus, memegang dua label pengiriman dan membandingkannya dengan wajah curiga.
4. Frans menunjukkan label pengiriman yang tertukar kepada Pak Darma di meja gudang, Rina berdiri di samping dengan wajah khawatir.
5. Pak Darma memeriksa label dan daftar kiriman di meja, wajahnya berubah kaget dan menyesal, Frans berdiri tenang di sampingnya.
6. Pak Darma menjabat tangan Frans sambil menunduk meminta maaf, Rina tersenyum lega di belakang mereka.
7. Frans berdiri di depan rekan-rekan gudang memakai seragam baru Operational Manager dengan papan nama, semua bertepuk tangan, suasana hangat.

## Prompt gerakan per adegan (Bahasa Indonesia sederhana, DINAMIS — gerakan tokoh HARUS jelas terlihat; selalu diakhiri "static locked camera, no zoom, no camera movement")

1. Pak Darma menunjuk Frans dengan tegas sambil menggeleng marah, Frans menunduk sopan lalu berjalan pergi dengan tenang, static locked camera, no zoom, no camera movement
2. Frans rukuk lalu sujud dengan tenang di musala, kemudian berdiri dan melipat sajadahnya, static locked camera, no zoom, no camera movement
3. Frans membolak-balik label pengiriman, mengangkat dua label tinggi-tinggi dan membandingkannya, matanya membesar kaget, static locked camera, no zoom, no camera movement
4. Frans menyerahkan label kepada Pak Darma sambil menunjuk alamat yang salah, Pak Darma mengambil dan membaca label itu, static locked camera, no zoom, no camera movement
5. Pak Darma membandingkan label dengan daftar kiriman, mengangguk pelan lalu menepuk dahinya menyesal, static locked camera, no zoom, no camera movement
6. Pak Darma mengulurkan tangan menjabat tangan Frans sambil menunduk, Frans tersenyum menerima jabatan itu, static locked camera, no zoom, no camera movement
7. Frans melangkah maju dengan percaya diri memakai seragam baru, rekan-rekan bertepuk tangan meriah, static locked camera, no zoom, no camera movement

## Kuota & rencana cadangan (PENTING — belajar dari episode 4)

- Episode 4 (17 Nov): Wan2GP 5B butuh hampir 2 jam untuk 7 adegan — upload telat ~45 menit (tayang 17:16, target 16:30). **Mulai produksi pagi/siang 18 Nov, jangan menunggu 15:00.**
- Prioritaskan animasi untuk adegan 1, 3, 5, 7 (paling dramatis). Adegan 2, 4, 6 boleh pakai gambar diam + zoom pelan di editor kalau GPU/kuota habis.
- Kalau satu klip gagal, jangan diulang berkali-kali (boros kuota) — rakit dari yang berhasil dan laporkan durasi sebenarnya dengan jujur.
- Akun HF Idza-dev daftar lewat Google — TIDAK punya password HF; kalau browser minta login, login via "Continue with Google", jangan pakai password.

## Caption (siap copas)

DIANCAM POTONG GAJI GARA-GARA SHOLAT! 😱

Frans, staf gudang, pamit sholat... bosnya malah mengancam potong gaji!

Tapi Frans tetap teguh. Dan justru karena keteguhannya itu, dia menemukan label kiriman yang tertukar — perusahaan selamat dari kerugian besar! 🥹

Moral: Orang yang teguh pada prinsipnya tidak akan pernah rugi.

Kalau kamu jadi Frans, apa yang kamu lakukan? Tulis di komentar 👇

#FYP #Viral #KisahInspiratif #Sholat #Kebaikan #ReelsInspiratif #CeritaHidup

## Setelah tayang

- Catat tema, nama (Frans, Pak Darma, Rina), dan deskripsi wajah ke `hidden_files/log-tema.md` supaya episode berikutnya tidak mengulang.
- Arsipkan brief ini juga ke repo GitHub `mahendraidza-spec/Reels-inspiratif` (Idza: GitHub write actions "always approved" — jalankan, dia menyetujui kartu persetujuannya).
