# Naskah Episode 7 — Jumat 20 Nov 2026 (Flow + stills; Wan 2.2 habis)

> **NASKAH — ditulis 20 Nov ~15:05 WIB, saat cron 15:00 jalan.** Episode 6 ("Becak Tua Menembus Hujan", Pak Wiryo) tayang 19 Nov ~15:08 WIB.
>
> **STATUS KUOTA HARI INI (20 Nov, dari log harian — BUKAN tebakan):**
> - **Wan 2.2 (HF Space, Idza-dev): KUOTA HABIS.** Produksi podcast 20 Nov mencoba 2x (12:31–12:38 WIB) kena "daily ZeroGPU limit". Meter periode 3,1/5 mnt (sisa 1,9 mnt, periode berakhir 1 Des) tapi cap harian terpisah sudah habis. **Tidak ada klip Wan yang bisa dibuat hari ini — jangan dicoba ulang.**
> - **Google Flow akun utama (mahendra.idza@gmail.com): STATUS BELUM PASTI.** Refresh harian ~01:27 WIB — kalau belum dipakai hari ini, seharusnya kembali 50 kredit (10/klip 8 detik tidak cukup... koreksi: 20 kredit/klip → 2 klip = 40 kredit). **Dicoba SATU kali via browser untuk 2 klip (adegan 1 pembuka + adegan 6 serah-terima sepeda).** PERHATIAN: Secure Vault kini hanya menyimpan SATU login google.com — setelah login Deni disimpan 20 Nov ~13:06, belum jelas apakah login akun utama ketimpa. Kalau browser gagal login / kata sandi ditolak, JANGAN minta kata sandi ke user, langsung lanjut versi stills.
> - **Google Flow akun Deni Antono: SISA 10 KREDIT** (50 → 10 setelah 2 klip podcast v2 siang ini). Satu klip butuh 20 → **tidak bisa dipakai.**
> - **Wan2GP Colab: DIBATALKAN Idza 18 Nov ("kurang sip").** **Jimeng/Douyin: DITUNDA Idza.** **media.generate_video: 403 permanen — tidak dicoba ulang.**
>
> **KEPUTUSAN PRODUKSI EPISODE 7:** bangun dulu versi **stills + zoom sangat pelan** (pola ep. 6, layak upload) supaya ada video siap tayang jam 16:30. Sambil itu coba Flow akun utama untuk 2 klip gerak (adegan 1 + 6); kalau berhasil, rakit ulang dengan klip itu (assemble.sh otomatis pakai klip kalau ada di clips-2026-11-20/). Kalau gagal, tayang versi stills dan laporkan jujur ke Idza.

- **Judul:** "Sepeda Guru Ngaji Dicuri, Balasan Warga Bikin Nangis!"
- **Jadwal:** produksi jam 15:00, upload 16:30 WIB ke profil pribadi (facebook.com/idzaa23), seperti biasa.
- **Durasi target:** 7 adegan × ±3–4 detik ≈ 25 detik, vertikal 9:16.
- **Aturan (perintah Idza 15 Nov 23:35 WIB): episode WAJIB ada dialog percakapan karakter utama, dari adegan awal sampai akhir — bukan cuma di akhir. Bentuk dialog: SUARA (TTS).** Suara: Pak Hadi = laki-laki (avocado_v2:MAI_03, nada tenang dan hangat), Rizki = anak laki-laki (MAI_03, nada ceria), Bu Aminah = perempuan (avocado_v2:MAI_01). TTS dibuat per adegan, dicampur di atas musik dengan musik lebih pelan; **tiap adegan dialognya MAKS ~70 karakter total supaya muat dalam ±5 detik.** **Watermark (perintah Idza 15 Nov 23:39 WIB): teks idza.mahendra tanpa tanda petik, di pojok kanan atas video, semi-transparan, terbaca tapi tidak menutupi adegan/wajah — dipasang saat assembly.**
- **Edit MAKSIMAL (perintah Idza 15 Nov 23:34 WIB, biar FYP meledak): hook kuat di 3 detik pertama (guru ngaji + sepeda tua + anak-anak melambaikan tangan); konteks karakter + cerita jelas sejak adegan 1; musik emosional yang naik ke klimaks; tidak ada adegan mati; thumbnail clickbait wajib.**
- **Thumbnail clickbait (wajib):** frame adegan 3 (Pak Hadi terduduk lemas di depan musala, sepeda hilang) + teks besar "SEPEDA GURU NGAJI DICURI!" + sub-teks "Balasan Warga Bikin Nangis"

## Tokoh (BARU — beda dari Slamet, Pak Darno, Mas Budi, Pak Sastro, Dimas, Bu Ratna, Frans, Pak Darma, Rina, Pak Wiryo, Bu Sari, dan Aldi)

**Pak Hadi, 52 tahun, guru ngaji keliling.** Rambut hitam beruban pendek, kumis tipis, kulit sawo matang, baju koko putih, sarung batik coklat, peci hitam, sepeda ontel tua hitam dengan keranjang berisi Al-Qur'an. Wajah dan ciri ini dipakai SAMA PERSIS di semua prompt gambar adegan 1–7.

**Rizki, 9 tahun, murid ngaji.** Rambut hitam pendek, baju koko putih, peci putih, tas selempang kecil.

**Bu Aminah, 45 tahun, ibu Rizki.** Kerudung ungu, daster bunga.

## Cerita (gaya EL BORA TV: orang biasa berbuat baik → konflik → pertolongan datang → moral)

1. **Pagi cerah.** Pak Hadi mengayuh sepeda ontel tuanya keliling kampung menuju musala, anak-anak melambaikan tangan dari pinggir jalan.
2. **Di musala.** Pak Hadi mengajar anak-anak mengaji, Rizki membaca Al-Qur'an dengan semangat.
3. **Sepeda hilang.** Pulang mengajar, sepeda ontel Pak Hadi HILANG — dicuri. Pak Hadi terduduk lemas di depan musala.
4. **Rizki mengadu.** Rizki pulang dan bercerita panik ke ibunya, Bu Aminah terkejut.
5. **Patungan warga.** Sore hari di musala, warga dan anak-anak mengumpulkan uang patungan, celengan ayam dibuka di atas tikar.
6. **Sepeda baru.** Keesokan pagi, Bu Aminah dan warga menyerahkan sepeda ontel baru mengkilap ke Pak Hadi di depan musala.
7. **Kembali mengajar.** Pak Hadi tersenyum naik sepeda barunya di jalan kampung yang cerah, anak-anak melambaikan tangan.

**Moral (teks di caption, bukan di video):** "Kebaikan yang ditanam dengan ikhlas, akan kembali dengan cara yang tak disangka."

## Dialog percakapan per adegan (WAJIB — karakter ngomong dari adegan awal, bukan cuma di akhir; DIPENDEKKAN, maks ~70 karakter per adegan supaya muat ±5 detik)

1. Pak Hadi: "Ayo, Nak. Ngaji dulu sebelum berangkat sekolah."
2. Rizki: "Pak, saya sudah hafal surat pendek!"
3. Pak Hadi: "Sepeda saya... hilang? Ya Allah..."
4. Rizki: "Bu, sepeda Pak Hadi dicuri orang!"
5. Bu Aminah: "Ayo patungan. Beliau sudah banyak berbuat baik."
6. Bu Aminah: "Pak, ini sepeda baru dari kami semua."
7. Pak Hadi: "Terima kasih. Kebaikan selalu kembali."

## Prompt gambar per adegan (karakter sama persis di semua adegan)

Ciri tokoh yang diulang verbatim di tiap prompt gambar: "Pak Hadi, 52 tahun, guru ngaji keliling Indonesia, rambut hitam beruban pendek, kumis tipis, baju koko putih, sarung batik coklat, peci hitam, sepeda ontel tua hitam dengan keranjang berisi Al-Qur'an" dan "Rizki, 9 tahun, anak laki-laki, rambut hitam pendek, baju koko putih, peci putih" dan "Bu Aminah, 45 tahun, ibu Indonesia, kerudung ungu, daster bunga".

1. Pagi cerah di jalan kampung Indonesia, Pak Hadi mengayuh sepeda ontel tuanya menuju musala, anak-anak melambaikan tangan dari pinggir jalan, suasana hangat dan ceria.
2. Di dalam musala kecil yang tenang, Pak Hadi mengajar anak-anak mengaji, Rizki membaca Al-Qur'an dengan semangat, cahaya pagi masuk dari jendela.
3. Siang hari di depan musala kecil, Pak Hadi terduduk lemas di tanah, sepeda ontelnya hilang dicuri, hanya rantai putus tergeletak, wajah sedih dan bingung.
4. Di rumah sederhana, Rizki bercerita panik kepada Bu Aminah sambil menunjuk ke arah musala, Bu Aminah terkejut memegang dada.
5. Sore hari di musala, warga dan anak-anak mengumpulkan uang patungan di atas tikar, celengan ayam dibuka, suasana gotong royong yang hangat.
6. Pagi cerah di depan musala, Bu Aminah dan warga menyerahkan sepeda ontel baru yang mengkilap kepada Pak Hadi, Pak Hadi terharu memegang dada.
7. Pak Hadi tersenyum naik sepeda ontel barunya di jalan kampung yang cerah, anak-anak melambaikan tangan dengan gembira, suasana hangat.

## Prompt gerakan per adegan (untuk Flow — Bahasa Indonesia sederhana, selalu diakhiri "static locked camera, no zoom, no camera movement")

1. Pak Hadi mengayuh sepeda ontel pelan sambil tersenyum, anak-anak melambaikan tangan, static locked camera, no zoom, no camera movement
2. Rizki membaca Al-Qur'an dengan semangat, Pak Hadi mengangguk tersenyum, static locked camera, no zoom, no camera movement
3. Pak Hadi menunduk lemas lalu menatap tempat sepeda yang hilang, static locked camera, no zoom, no camera movement
4. Rizki bercerita dengan panik sambil menunjuk ke arah musala, Bu Aminah terkejut, static locked camera, no zoom, no camera movement
5. Warga memasukkan uang ke dalam wadah patungan, anak-anak membuka celengan ayam, static locked camera, no zoom, no camera movement
6. Bu Aminah menyerahkan sepeda baru kepada Pak Hadi, Pak Hadi terharu memegang dada, static locked camera, no zoom, no camera movement
7. Pak Hadi mengayuh sepeda baru pelan sambil tersenyum, anak-anak melambaikan tangan, static locked camera, no zoom, no camera movement

## Kuota & rencana cadangan

- Wan 2.2 kuota habis hari ini (12:31–12:38 WIB) — jangan dicoba ulang. Flow Deni sisa 10 kredit — tidak bisa. Flow utama dicoba 1x untuk adegan 1 + 6; kalau login gagal / kredit kurang, lanjut versi stills.
- Kalau satu klip gagal, jangan diulang berkali-kali (boros kuota) — rakit dari yang berhasil dan laporkan durasi sebenarnya dengan jujur.
- Akun HF Idza-dev daftar lewat Google — TIDAK punya password HF; kalau browser minta login, login via "Continue with Google", jangan pakai password.

## Caption (siap copas)

SEPEDA GURU NGAJI INI DICURI, TAPI BALASAN WARGA BIKIN NANGIS! 🥹

Setiap pagi Pak Hadi keliling kampung naik sepeda ontel tuanya, mengajar anak-anak mengaji dengan ikhlas, tanpa pernah meminta bayaran...

Sampai suatu siang, sepedanya HILANG dicuri orang! 😭

Tapi lihat apa yang dilakukan warga... bikin merinding!

Moral: Kebaikan yang ditanam dengan ikhlas, akan kembali dengan cara yang tak disangka.

Kalau kamu jadi warga kampung itu, apa yang kamu lakukan? Tulis di komentar 👇

#FYP #Viral #KisahInspiratif #GuruNgaji #Kebaikan #ReelsInspiratif #CeritaHidup

## Setelah tayang

- Catat tema, nama (Pak Hadi, Rizki, Bu Aminah), dan deskripsi wajah ke `hidden_files/log-tema.md` supaya episode berikutnya tidak mengulang.
- Arsipkan brief ini juga ke repo GitHub `mahendraidza-spec/Reels-inspiratif` (Idza: GitHub write actions "always approved" — jalankan, dia menyetujui kartu persetujuannya).
