# IFRWP5149_2406005_LabAlat

## Identitas

- **NIM:** 2406005
- **Nama:** Siti Maulida Rahayu
- **Mata Kuliah:** IFRWP5149 — Praktikum Analisis dan Desain Berorientasi Objek
- **Semester:** 5
- **Program Studi:** S1 Teknik Informatika, Institut Teknologi Garut
- **Kakas:** draw.io / diagrams.net

## Studi Kasus

**Sistem Informasi Peminjaman dan Pengembalian Peralatan Laboratorium Kampus** (kode `LAB`), dengan studi kasus tugas **Sistem Informasi Akademik** (kode `SIA`).

Skenario adalah bahan latihan yang ditetapkan jobsheet, bukan hasil pengumpulan kebutuhan laboratorium atau institusi nyata.

## Ringkasan Status Pertemuan 1–6

| Pertemuan | Materi | Hasil utama | Status |
|---|---|---|---|
| 1 | Pengenalan lingkungan praktikum dan kakas UML | Workspace, README, logbook, diagram activity latihan (S-ORI-01) | Latihan — belum divalidasi sebagai model proses |
| 2 | Notasi dasar UML | Use case diagram sederhana (aktor, use case, batas sistem, asosiasi); SIA: perbaikan 4 kesalahan notasi | Latihan notasi |
| 3 | Use case diagram dan use case description | 7 use case LAB, include (UC03→UC04), extend (UC05→UC03), deskripsi; SIA: KRS | Latihan use case diagram |
| 4 | Use case diagram kumulatif | 5 aktor, 12 use case, 2 collaboration, 17 hubungan (generalization aktor dan use case); SIA: Layanan Hasil Studi (SIA-UC07–UC13) | Model analisis |
| 5 | Skenario use case | 12 tabel skenario LAB (telaah terhadap diagram P04) dan 7 tabel skenario SIA | Model analisis |
| 6 | Activity diagram dari skenario | 7 activity diagram LAB dan activity diagram SIA (Input Nilai sampai Lihat KHS serta kelola data mahasiswa) | Model analisis |
| 7 | Assessment Pertemuan 1–6 | Lihat bagian Assessment di bawah | Menyusul |

## Struktur Folder

```text
IFRWP5149_2406005_LabAlat/
├── 00_administrasi/
│   ├── P01_2406005_logbook_v01.md
│   ├── P02_2406005_logbook_v01.md
│   ├── P03_2406005_logbook_v01.md
│   ├── P04_2406005_logbook_v01.md
│   ├── P05_2406005_logbook_v01.md
│   └── P06_2406005_logbook_v01.md
├── 01_skenario/
│   ├── P02_LAB_scenario_v01.md
│   ├── P02_SIA_scenario_v01.md
│   ├── P03_LAB_scenario_v01.md
│   ├── P03_SIA_scenario_v01.md
│   ├── P04_LAB_kebutuhan_v01.md
│   ├── P04_LAB_skenario_v01.md
│   ├── P04_SIA_kebutuhan_v01.md
│   ├── P04_SIA_skenario_v01.md
│   ├── P05_2406005_LAB_skenario_v01.md
│   ├── P05_2406005_SIA_skenario_v01.md
│   └── S-ORI-01_orientasi_kasus_v01.md
├── 02_template/
│   ├── P01_metadata_artefak_v01.md
│   ├── P02_metadata_artefak_v01.md
│   ├── P03_metadata_artefak_v01.md
│   ├── P04_metadata_artefak_v01.md
│   ├── P05_metadata_artefak_vo1.md
│   ├── P06_metadata_artefak_vo1.md
│   └── template_metadata_artefak_v01.md
├── 03_latihan_tools/
│   ├── P01/
│   │   ├── file.md
│   │   └── file.md.txt
│   ├── P02/
│   │   ├── LAB/
│   │   │   ├── P02_2406005_LAB_notasi_usecase_v01.drawio
│   │   │   ├── P02_2406005_LAB_notasi_usecase_v01.drawio .png
│   │   │   └── file.md
│   │   └── SIA/
│   │       ├── P01_2406005_latihan_activity_v01.drawio
│   │       ├── P01_2406005_latihan_activity_v01.png.png
│   │       ├── P02_2406005_SIA_notasi_v01.drawio
│   │       ├── P02_2406005_SIA_notasi_v01.drawio.png
│   │       └── file.md
│   ├── P03/
│   │   ├── LAB/
│   │   │   ├── P03_2406005_LAB_deskripsi_v01.md
│   │   │   ├── P03_2406005_LAB_usecase_v01.drawio
│   │   │   ├── P03_2406005_LAB_usecase_v01.png
│   │   │   └── file.md
│   │   ├── SIA/
│   │   │   ├── P03_2406005_SIA_deskripsi_v01.md
│   │   │   ├── P03_2406005_SIA_usecase_v01.drawio
│   │   │   ├── P03_2406005_SIA_usecase_v01.png
│   │   │   └── file.md
│   │   └── file.md
│   └── P04/
│       ├── LAB/
│       │   ├── P03_2406005_LAB_usecase_v01.drawio
│       │   └── P03_2406005_LAB_usecase_v01.png
│       └── SIA/
│           ├── P04_2406005_SIA_deskripsi_v01.md
│           ├── P04_2406005_SIA_usecase_v01.drawio
│           └── P04_2406005_SIA_usecase_v01.png
├── 04_model_analisis/
│   ├── P03/
│   │   └── LAB/
│   │       └── P03_2406005_LAB_model_analisiss_v01.md
│   ├── P04/
│   │   ├── LAB/
│   │   │   ├── P04_2406005_LAB_usecase_v01.drawio
│   │   │   └── P04_2406005_LAB_usecase_v01.png
│   │   └── SIA/
│   │       ├── P04_2406005_SIA_deskripsi_v01.md
│   │       ├── P04_2406005_SIA_usecase_v01.drawio
│   │       └── P04_2406005_SIA_usecase_v01.png
│   ├── P05/
│   │   ├── LAB/
│   │   │   └── P05_2406005_LAB_skenario_v01.drawio
│   │   └── SIA/
│   │       └── P05_2406005_SIA_skenario_v01.drawio
│   ├── P06/
│   │   ├── LAB/
│   │   │   ├── P06_2406005_LAB_activity_cetak_bukti_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_cetak_bukti_v01.png
│   │   │   ├── P06_2406005_LAB_activity_kelola_data_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_kelola_data_v01.png
│   │   │   ├── P06_2406005_LAB_activity_keputusan_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_keputusan_v01.png
│   │   │   ├── P06_2406005_LAB_activity_laporan_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_laporan_v01.png
│   │   │   ├── P06_2406005_LAB_activity_lihat_ketersediaan_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_lihat_ketersediaan_v01.png
│   │   │   ├── P06_2406005_LAB_activity_peminjaman_v01.drawio
│   │   │   ├── P06_2406005_LAB_activity_peminjaman_v01.png
│   │   │   ├── P06_2406005_LAB_activity_pengembalian_v01.drawio
│   │   │   └── P06_2406005_LAB_activity_pengembalian_v01.png
│   │   └── SIA/
│   │       ├── P06_2406005_SIA_activity_hapus_data_mahasiswa_v01.drawio
│   │       ├── P06_2406005_SIA_activity_hapus_data_mahasiswa_v01.drawio.png
│   │       ├── P06_2406005_SIA_activity_input_nilai_mata_kuliah_v01.drawio.drawio
│   │       ├── P06_2406005_SIA_activity_input_nilai_mata_kuliah_v01.drawio.drawio.png
│   │       ├── P06_2406005_SIA_activity_kelola_data_v01.drawio
│   │       ├── P06_2406005_SIA_activity_kelola_data_v01.drawio.png
│   │       ├── P06_2406005_SIA_activity_lihat_kalender_akademik_v01.drawio
│   │       ├── P06_2406005_SIA_activity_lihat_kalender_akademik_v01.drawio.png
│   │       ├── P06_2406005_SIA_activity_lihat_khs_v01.drawio
│   │       ├── P06_2406005_SIA_activity_lihat_khs_v01.drawio.png
│   │       ├── P06_2406005_SIA_activity_tambah_data_mahasiswa_v01.drawio
│   │       ├── P06_2406005_SIA_activity_tambah_data_mahasiswa_v01.drawio.png
│   │       ├── P06_2406005_SIA_activity_ubah_data_mahasiswa_v01.drawio
│   │       ├── P06_2406005_SIA_activity_ubah_data_mahasiswa_v01.drawio.png
│   │       ├── P06_2406087_SIA_activity_v01.drawio
│   │       └── catatan.drawio
│   └── file.md
├── 05_model_desain/
│   └── v01.md
├── 06_laporan/
│   ├── P01_2406005_laporan_singkat_v01.md
│   ├── P02_2406005_jobsheet_review_v01.md
│   ├── P03_2406005_jobsheet_review_v01.md
│   └── P04_2406005_jobsheet_review_v01
└── README.md
```

Catatan: `05_model_desain` belum berisi model desain (hanya `v01.md`). Berkas `file.md` pada beberapa folder adalah penanda folder.

## Penamaan Berkas

Pola: `P<dua digit>_<NIM>_<KASUS>_<ARTEFAK>_v<NN>.<ekstensi>`

- `LAB` = laboratorium, `SIA` = akademik.
- Nomor versi berkas sumber dan ekspor harus sama.
- Naik ke `v02` hanya setelah ada perubahan isi dari review, dan dicatat di metadata serta logbook.
- `.drawio` adalah berkas sumber yang dapat disunting; `.png` adalah hasil ekspor untuk peninjauan.

## Daftar Berkas per Pertemuan

### Pertemuan 1
- Latihan activity: `P01_2406005_latihan_activity_v01.drawio` dan `.png.png` (di `03_latihan_tools/P02/SIA/`)
- Skenario: `S-ORI-01_orientasi_kasus_v01.md`
- Metadata: `P01_metadata_artefak_v01.md`; logbook: `P01_2406005_logbook_v01.md`; laporan: `P01_2406005_laporan_singkat_v01.md`

### Pertemuan 2 (`03_latihan_tools/P02/`)
- LAB: `P02_2406005_LAB_notasi_usecase_v01.drawio` dan `.drawio .png`
- SIA: `P02_2406005_SIA_notasi_v01.drawio` dan `.drawio.png`
- Skenario: `P02_LAB_scenario_v01.md`, `P02_SIA_scenario_v01.md`
- Review: `P02_2406005_jobsheet_review_v01.md`

### Pertemuan 3 (`03_latihan_tools/P03/`)
- LAB: `P03_2406005_LAB_usecase_v01.drawio` / `.png`, `P03_2406005_LAB_deskripsi_v01.md`
- SIA: `P03_2406005_SIA_usecase_v01.drawio` / `.png`, `P03_2406005_SIA_deskripsi_v01.md`
- Model analisis: `04_model_analisis/P03/LAB/P03_2406005_LAB_model_analisiss_v01.md`
- Skenario: `P03_LAB_scenario_v01.md`, `P03_SIA_scenario_v01.md`
- Review: `P03_2406005_jobsheet_review_v01.md`

### Pertemuan 4 (`04_model_analisis/P04/`)
- LAB: `P04_2406005_LAB_usecase_v01.drawio` / `.png`
- SIA: `P04_2406005_SIA_usecase_v01.drawio` / `.png`, `P04_2406005_SIA_deskripsi_v01.md`
- Kebutuhan dan skenario: `P04_LAB_kebutuhan_v01.md`, `P04_LAB_skenario_v01.md`, `P04_SIA_kebutuhan_v01.md`, `P04_SIA_skenario_v01.md`
- Review: `P04_2406005_jobsheet_review_v01`

### Pertemuan 5
- `01_skenario/P05_2406005_LAB_skenario_v01.md` dan `P05_2406005_SIA_skenario_v01.md`
- `04_model_analisis/P05/LAB/P05_2406005_LAB_skenario_v01.drawio`
- `04_model_analisis/P05/SIA/P05_2406005_SIA_skenario_v01.drawio`

### Pertemuan 6 (`04_model_analisis/P06/`)
- LAB (7 activity, masing-masing `.drawio` + `.png`): `cetak_bukti`, `kelola_data`, `keputusan`, `laporan`, `lihat_ketersediaan`, `peminjaman`, `pengembalian`
- SIA (masing-masing `.drawio` + `.png`): `input_nilai_mata_kuliah`, `lihat_khs`, `lihat_kalender_akademik`, `kelola_data`, `tambah_data_mahasiswa`, `ubah_data_mahasiswa`, `hapus_data_mahasiswa`, serta `P06_2406087_SIA_activity_v01.drawio` dan `catatan.drawio`

## Assessment Pertemuan 7 (Pertemuan 1–6)

### A. Capaian per pertemuan

Centang setelah Anda memeriksa hasilnya, bukan sebelum.

**Pertemuan 1 — Workspace dan kakas**
- [✓] Folder induk `IFRWP5149_2406005_LabAlat` dan subfolder sesuai SOP
- [✓] README, logbook, dan template metadata tersedia
- [✓] Diagram latihan memuat 4 elemen dan 3 alur, berstatus belum divalidasi
- [✓] Berkas `.drawio` dapat dibuka kembali; PNG sesuai versi terakhir

**Pertemuan 2 — Notasi UML**
- [✓] Aktor di luar batas sistem, use case berbentuk elips di dalam batas sistem
- [✓] Asosiasi berupa garis utuh tanpa panah, tanpa garis antar use case
- [✓] SIA: 4 kesalahan notasi ditemukan dan diperbaiki (aktor di dalam batas, kotak bukan elips, asosiasi salah, judul salah)
- [✓] Metadata `LAB-P02-UC` terisi; versi v01/v02 tercatat

**Pertemuan 3 — Use case diagram dan description**
- [✓] 3 aktor, 7 use case LAB, dan relasi sesuai katalog
- [✓] `include` LAB-UC03 → LAB-UC04; `extend` LAB-UC05 → LAB-UC03 dengan condition dan extension point
- [✓] Deskripsi use case lengkap (pemicu, prasyarat, alur utama, alternatif, pascakondisi)
- [✓] SIA: katalog, include/extend, empat deskripsi, dan uji konsistensi tiga situasi

**Pertemuan 4 — Diagram kumulatif**
- [✓] LAB: 5 aktor, 12 use case, 2 collaboration, 17 hubungan
- [✓] SIA: SIA-UC07 sampai SIA-UC13 beserta generalization
- [✓] Berkas P03 tidak ditimpa

**Pertemuan 5 — Skenario use case**
- [✓] 12 tabel LAB ditelaah dan dicocokkan dengan diagram P04 (kolom penelusuran terisi)
- [✓] 7 tabel SIA lengkap: Nama, Aktor, Tujuan, Deskripsi, Kegiatan/Respon sistem, Normal, Alternative, Akhir
- [✓] Penomoran berlanjut dari Skenario Normal ke Alternative
- [✓] Include sebagai langkah rujukan; extend sebagai cabang bersyarat; collaboration tanpa langkah sendiri

**Pertemuan 6 — Activity diagram**
- [✓] 7 activity LAB (UC01, UC02, UC03, UC05, UC06, UC07, UC11), masing-masing `.drawio` + `.png`
- [✓] Tepat satu initial node, minimal satu activity final node, tidak ada action terputus
- [✓] Semua alur keluar decision memiliki guard; fork selalu berpasangan dengan join
- [✓] Action berada pada swimlane aktor yang benar; Kepala Laboratorium hanya muncul di Activity Laporan
- [✓] "Periksa kelengkapan aksesori peralatan" ditandai sebagai unsur proses baru
- [✓] Activity Keputusan dikerjakan mandiri sebelum membuka pembanding; perbedaan dicatat
- [✓] SIA: 4 swimlane, decision [lengkap]/[belum lengkap], satu pasang fork–join

### B. Rangkuman konsep lintas pertemuan

| Konsep | Ringkasan | Pertemuan |
|---|---|---|
| Berkas sumber vs ekspor | `.drawio` adalah sumber; PNG hanya untuk tinjauan | 1, 2 |
| Penamaan dan versi | Pola `P<NN>_<NIM>_<KASUS>_<ARTEFAK>_v<NN>`; versi sumber dan ekspor sama | 1–6 |
| Aktor dan batas sistem | Aktor di luar batas, use case di dalam | 2, 3 |
| Asosiasi | Menunjukkan partisipasi, bukan alur proses | 2, 3 |
| Include | Perilaku wajib; panah dari penyerta ke yang disertakan | 3, 4, 5, 6 |
| Extend | Perilaku bersyarat; panah dari tambahan ke dasar; punya condition dan extension point | 3, 4, 5, 6 |
| Generalization | Aktor umum (satu skenario) dan use case umum (skenario pembeda) | 4, 5 |
| Collaboration | Tidak punya langkah atau tabel skenario sendiri; tidak digambar di activity | 4, 5, 6 |
| Skenario | Tabel Kegiatan/Respon sistem; penomoran berlanjut ke Alternative | 5 |
| Activity diagram | Diturunkan dari skenario: normal → alur utama, alternative → decision, include → action wajib, extend → cabang bersyarat | 6 |

## Kesimpulan

Pertemuan 1–6 membangun alur kerja pemodelan secara bertahap: mulai dari penyiapan workspace dan kakas draw.io, notasi dasar UML, use case diagram dan description, diagram kumulatif, tabel skenario, hingga activity diagram yang tertelusur ke langkah skenario. Seluruh artefak disimpan dengan penamaan dan versi yang konsisten agar mudah diperiksa dan dilanjutkan.
