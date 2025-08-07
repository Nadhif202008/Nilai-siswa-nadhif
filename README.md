# 📚 Sistem Pengelolaan Nilai Siswa

Sistem ini digunakan untuk mencatat dan mengevaluasi nilai siswa berdasarkan mata pelajaran yang diambil. Sistem menyimpan data seperti nama siswa, NIS, nilai-nilai per mata pelajaran, serta melakukan perhitungan rata-rata, nilai tertinggi, dan nilai terendah.

---

## 📌 Fitur Utama

- Input data siswa (Nama, NIS)
- Input nilai tiap mata pelajaran
- Hitung nilai rata-rata, tertinggi, dan terendah
- Penentuan kelulusan berdasarkan kriteria nilai

---

## 🗂️ Struktur Database

Struktur database terdiri dari 4 tabel utama:

- `Siswa`: Informasi data siswa
- `MataPelajaran`: Daftar mata pelajaran
- `Nilai`: Nilai per siswa per mata pelajaran
- `RekapNilai`: Rekap nilai siswa (rata-rata, tertinggi, terendah)

📎 Diagram database tersedia pada file:  
[untitled.svg](untitled.svg)

---

## 🔁 Flowchart Proses Nilai

Flowchart menggambarkan proses input data, perhitungan nilai, dan keputusan lulus/tidak lulus berdasarkan nilai minimal 75.

📎 Flowchart tersedia pada file:  
[zzz.svg](zzz.svg)

---

## 🛠️ Teknologi yang Disarankan

- DBMS: MySQL / PostgreSQL / SQLite
- Frontend: HTML, CSS, JS (opsional)
- Backend: Node.js / PHP / Python / Laravel / Express

---

## 📌 Ketentuan Kelulusan

Seorang siswa dinyatakan **Lulus** jika rata-rata nilai ≥ 75.  
Jika tidak, maka dinyatakan **Tidak Lulus**.

---

## 🧪 Contoh Nilai

| Nama        | NIS       | Mapel          | Nilai |
|-------------|-----------|----------------|--------|
| Andi        | 123456789 | Matematika     | 80     |
| Andi        | 123456789 | IPA            | 90     |
| Andi        | 123456789 | IPS            | 70     |
| Andi        | 123456789 | Bahasa Indo    | 85     |

Rata-rata: **81.25** → ✅ Lulus

---

## 👨‍💻 Kontributor

- 📌 Dibuat oleh: **[Nama Anda]**
- 🗓️ Tanggal: Agustus 2025
