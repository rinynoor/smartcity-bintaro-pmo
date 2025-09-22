# Gantt Chart - Jadwal Proyek Smart City Bintaro

```mermaid
gantt
    title Gantt Chart - Smart City Bintaro
    dateFormat  YYYY-MM-DD
    axisFormat  %d-%b

    section Perencanaan & Infrastruktur
    Analisis Kebutuhan                :a1, 2025-01-06, 2025-03-02
    Desain Arsitektur                :a2, 2025-03-03, 2025-03-30
    Infrastruktur IoT & CCTV         :a3, 2025-03-31, 2025-06-22

    section Sprint (Agile)
    Sprint 1-3 (Login, Aduan, Dashboard) :s1, 2025-02-17, 2025-03-09
    Sprint 4-6 (IoT, Statistik, Notif)    :s2, 2025-03-10, 2025-03-30
    Sprint 7-10 (Waste, E-Gov, Pembayaran):s3, 2025-03-31, 2025-04-27
    Sprint 11-15 (CCTV AI, Statistik)     :s4, 2025-04-28, 2025-06-01
    Sprint 16 (Integrasi & Testing)       :s5, 2025-06-02, 2025-06-08

    section Uji & Peluncuran
    Pilot Test                            :p1, 2025-06-09, 2025-08-03
    Rollout Penuh                         :r1, 2025-08-04, 2025-12-07
