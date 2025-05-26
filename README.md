# ProjectISI

**ProjectISI** adalah proyek perangkat lunak yang dikembangkan menggunakan bahasa pemrograman Python dan Rust. Proyek ini mencakup beberapa komponen utama, termasuk antarmuka pengguna grafis (GUI), server, dan modul sensor. Tujuan dari proyek ini adalah untuk memantau dan mengelola data sensor secara real-time.

## Fitur

- **Antarmuka Pengguna Grafis (GUI):** Dibangun dengan Python, menyediakan visualisasi data dan kontrol interaktif.
- **Server:** Dikembangkan menggunakan Rust untuk performa tinggi dan efisiensi.
- **Modul Sensor:** Mengelola dan memproses data dari berbagai sensor.
- **Pengujian:** Skrip `test.py` untuk memastikan integritas dan kinerja sistem.

## Struktur Proyek
ProjectISI/
├── gui.py # PYQT
├── server/ # Kode sumber server (Rust)
├── Sensor/ # Modul pembacaan sensor
├── test.py # PYQT
└── README.md # Dokumentasi proyek

## Instalasi

1. **Kloning repositori:**

```bash
git clone https://github.com/Valzzsxs/ProjectISI.git
cd ProjectISI
2. **Instalasi dependensi Python:**
pip install -r requirements.txt


## Instalasi

1. **Kloning repositori:**

```bash
git clone https://github.com/Valzzsxs/ProjectISI.git
cd ProjectISI
Instalasi dependensi Python:

bash
Copy
Edit
pip install -r requirements.txt
Membangun server Rust:

bash
Copy
Edit
cd server
cargo build --release
Penggunaan
Menjalankan server:

bash
Copy
Edit
./server/target/release/server
Menjalankan GUI:

bash
Copy
Edit
python gui.py
Menjalankan pengujian:

bash
Copy
Edit
python test.py
Kontribusi
Kontribusi sangat dihargai! Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori ini dan ajukan pull request. Pastikan untuk mengikuti pedoman kontribusi yang telah ditetapkan.

Lisensi
Proyek ini dilisensikan di bawah MIT License.

Kontak
Untuk pertanyaan atau saran, silakan hubungi Valzzsxs.
