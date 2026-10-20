# Pengantar Teknologi Informasi

## Tugas PivotTable Microsoft Excel - Piksi Ganesha Clinic

Proyek tugas mata kuliah **Pengantar Teknologi Informasi**, menggunakan studi kasus fiktif kunjungan pasien rawat jalan di **Piksi Ganesha Clinic** periode Juli-September 2026. Seluruh rekaman merupakan **data dummy**, bukan data pasien nyata.

### Berkas

| Berkas | Kegunaan |
| --- | --- |
| [Tugas PivotTable - Piksi Ganesha Clinic.xlsx](Tugas%20PivotTable%20-%20Piksi%20Ganesha%20Clinic.xlsx) | Workbook interaktif (dataset, PivotTable, PivotChart, KPI, dan slicer) |
| [Tugas_PivotTable_Piksi_Ganesha_Clinic_Laporan.pdf](Tugas_PivotTable_Piksi_Ganesha_Clinic_Laporan.pdf) | Laporan PDF untuk pengumpulan: dashboard, ringkasan analisis, metodologi, dan lampiran 180 data |

### Isi dan fitur Excel

- `DATA_KUNJUNGAN`: 180 baris data kunjungan fiktif dengan sembilan kolom.
- `PIVOT_ANALISIS`: analisis jumlah kunjungan per poli, tren per bulan, jenis pembayaran/status, total nilai pelayanan per poli, serta tabel pembantu KPI.
- `DASHBOARD`: empat PivotChart, empat indikator KPI dinamis dengan `GETPIVOTDATA`, dan slicer interaktif **Bulan**, **Poli Tujuan**, serta **Jenis Pembayaran**.

### Ringkasan data (tanpa filter)

| Indikator | Hasil |
| --- | ---: |
| Total kunjungan | 180 |
| Status Selesai | 169 |
| Status Batal | 11 |
| Total nilai pelayanan simulasi | Rp12.520.000 |
| Kunjungan Poli Umum | 89 |
| Kunjungan Poli Gigi | 48 |
| Kunjungan Poli KIA | 43 |
| Juli / Agustus / September | 55 / 60 / 65 |

**Catatan:** Nominal biaya pelayanan merupakan data simulasi dan **bukan** bukti penerimaan pembayaran aktual maupun klaim BPJS.

### Cara membuka

1. Unduh atau buka berkas `.xlsx` menggunakan **Microsoft Excel desktop**.
2. Buka sheet `DASHBOARD`.
3. Gunakan slicer untuk memilih bulan, poli, atau jenis pembayaran. Gunakan ikon **Clear Filter** untuk kembali ke seluruh data.
4. Jika data ditambah atau berubah, pilih **Data > Refresh All** sebelum membaca ulang dashboard.
5. Untuk versi laporan yang tidak interaktif, buka berkas `.pdf`.

> Pratinjau GitHub tidak menjalankan fitur slicer dan PivotTable Excel. Unduh file `.xlsx` dan buka di Microsoft Excel desktop untuk menguji seluruh fungsinya.

**Mata kuliah:** Pengantar Teknologi Informasi  
**Bidang studi:** Manajemen Informasi Kesehatan (MIK)  
**Tujuan:** Pembelajaran pengolahan dan visualisasi data melalui Microsoft Excel.
