# Neuro Sleep by NeuroSynth

Aplikasi ini bertujuan untuk membantu Anda memahami pola tidur dan mengidentifikasi potensi gangguan tidur seperti Insomnia atau Sleep Apnea sebelum berdampak pada kehidupan sehari-hari. Dengan memasukkan data sederhana mengenai kebiasaan harian, aktivitas fisik, tanda vital, dan durasi tidur, aplikasi ini memberikan wawasan yang akurat dan personal tentang kesehatan tidur Anda dalam waktu singkat. Berdasarkan hasil ini, Anda dapat mengambil langkah-langkah yang tepat untuk memperbaiki kualitas tidur, meningkatkan energi, dan meningkatkan kesejahteraan secara keseluruhan.

# Developer:

221111320 - Nadiyah Shofa Salsabila

221110837 - Callisto Carlos

# Arsitektur & Teknologi

[Frontend UI (React)] <-> [Backend API (Flask)] <-> [Database (MySQL)] <-> [DevOps (Docker Container)]

Teknologi yang digunakan:
1. Bahasa Pemrograman: Python, JavaScript
2. Framework: Flask (untuk backend), React (untuk frontend)
3. Database: MySQL
4. Tools dan Pustaka:
   - Flask
   - Flask-Cors
   - python-dotenv
   - mysql-connector-python
   - joblib
   - numpy
   - scikit-learn
5. DevOps: Docker (untuk containerization dan deployment)

# Petunjuk Instalasi Lokal (Wajib via Docker)

### 1. Clone Repository
```bash
git clone https://github.com/NadiyahShofaSalsabila/Kelompok4-NeuroSleep.git
```

### 2. Konfigurasi `.env`
Buat file `.env` di root folder dengan isi seperti berikut:

```env
SECRET_KEY=your_secret_key_here

BACKEND_PORT=your_backend_port
FRONTEND_PORT=your_frontend_port

DB_HOST=your_database_host
DB_PORT=your_database_port
DB_DATABASE=your_database_name
DB_USERNAME=your_sql_username
DB_PASSWORD=your_sql_password

REACT_APP_API_URL=your_backend_host_(backend_port_optional)
```
atau bisa menggunakan perintah berikut:
```bash
cp .env.example .env
```

### 3. Jalankan Docker
```bash
docker-compose up --build
```

### 4. Jalankan website

http://localhost:3000 (Silahkan akses langsung di browser anda jika sudah berhasil melakukan instalasi lokal)

# Tata cara penggunaan aplikasi
Berikut ini lampiran tatacara penggunaan aplikasi NeuroSleep: https://drive.google.com/file/d/1ta3FYe5e37UTXSY1M31ClTxBekO5HFak/view?usp=drive_link
