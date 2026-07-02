# Legacy Prompt Integration

Dokumen ini menjelaskan bagaimana prompt lama OTNAY diserap ke sistem editorial baru.

## Prinsip
Prompt lama tidak dipakai mentah.
Ia dipecah menjadi beberapa lapisan:
- pilihan user
- commissioning
- brief editorial
- writing rule
- self-check
- brand memory

## Yang Diambil dari Prompt Lama
- pilihan tema
- pilihan nuansa emosi
- pilihan bentuk tulisan
- pilihan panjang
- pilihan jumlah karya
- larangan klise
- kewajiban tiap karya berbeda
- self-check sebelum final
- brand memory lintas karya

## Yang Tidak Dipertahankan Mentah
- tema klise sebagai default
- metafora bulan/senja/hujan sebagai pusat
- identitas akun sebagai “akun puisi”
- instruksi yang terlalu generik untuk semua karya

## Cara Masuk ke Sistem Baru
Prompt lama sekarang dibagi ke role berikut:
- `/commission` → menangani pilihan user dan kebutuhan tugas
- `/idea` → menerjemahkan pilihan menjadi keputusan editorial
- `/write` → menulis karya berdasarkan brief
- `/edit` → membedah hasil dan memilih final
- `/critic` → memberi veto
- `/blindtest` → mengecek identitas OTNAY
- `/archive` dan `/dna` → menjaga memori dan variasi lintas waktu

## Mapping Lama ke Sistem Baru
- Tema → Commission / Idea
- Nuansa Emosi → Commission / Idea / Brand
- Bentuk Tulisan → Commission / Write
- Panjang → Commission / Write
- Jumlah Karya → Commission / Write
- Self Check → Edit / Critic / Blindtest
- Brand Memory → Archive / DNA / Evolution

## Kesimpulan
Prompt lama sekarang jadi input layer.
Bukan operating system.
