# TrustLoker

**Cari magang dan kerja paruh waktu tanpa takut tertipu.**

TrustLoker adalah platform lowongan magang dan kerja paruh waktu untuk mahasiswa yang menaruh kepercayaan di garis depan. Setiap perusahaan punya *trust score* dan badge yang dihitung dari verifikasi identitas (NIB dan domain), riwayat aktivitas, dan hasil laporan. Listing mencurigakan dipindai otomatis, dilaporkan mahasiswa, lalu diperiksa admin. Perusahaan yang dilaporkan tetap berhak menyanggah (*right of reply*) sebelum sanksi dijatuhkan. Hasilnya: mahasiswa melamar dengan tenang, perusahaan yang jujur mendapat tempat, dan penipu kehabisan ruang.

## Identitas Kelompok

| No | Nama | NIM |
|---|---|---|
| 1 | Azzira Zahwa | 24343084 |
| 2 | Fa'iz Thahir Nasution | 24343035 |


## Struktur Repositori

```
TrustLoker/
├── Diagram/
│   ├── BPMN as-is & to-be.png
│   ├── User Persona.png
│   ├── Use Case.png
│   ├── Activity Diagram.png
│   └── Class Diagram.png
├── Dokumen/
│   ├── SRS_TrustLoker_v1.0.pdf
│   ├── UseCase_Specification.pdf
│   └── RTM_TrustLoker.pdf
└── README.md
```

## Isi Repositori

- **Diagram/**: BPMN As-is dan To-be, persona, use case diagram, tiga activity diagram, dan class diagram domain (21 kelas).
- **Dokumen/**: SRS v1.0 (33 kebutuhan fungsional, 24 use case, 25 kebutuhan nonfungsional), Use Case Specification, dan Requirements Traceability Matrix (FR, use case, dan class diagram).

## Ringkasan Sistem

- **Aktor:** Mahasiswa, Perusahaan, Admin; aktor sekunder Layanan Email dan Scheduler.
- **Fitur utama:** pencarian dan lamaran lowongan, verifikasi perusahaan, trust score dan badge, deteksi listing mencurigakan secara otomatis, pelaporan dengan hak jawab, dan moderasi admin.
- **Rencana teknologi:** Next.js, NestJS, Prisma, PostgreSQL, Redis/BullMQ, S3, GitHub Actions.
- **Metode pengembangan:** Agile (Scrum).
