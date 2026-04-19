# E-Commerce Data Analysis

## Pertanyaan Bisnis
- Pertanyaan 1 : Kategori produk apa yang memiliki rata-rata skor ulasan (review score) tertinggi dan terendah?
- Pertanyaan 2 : Bagaimana segmentasi pelanggan berdasarkan parameter RFM (Recency, Frequency, Monetary)?

## Setup Environment - Anaconda
- conda create --name main-ds python=3.12.3 (Versi yang saya gunakan dalam pengembangan)
- conda activate main-ds
- pip install -r requirements.txt

## Setup Environment - Shell/Terminal
- mkdir proyek_analisis_data
- cd proyek_analisis_data
- pipenv install
- pipenv shell
- pip install -r requirements.txt

## Run Streamlit App 
streamlit run dashboard/dashboard.py

## Catatan Dataset
**File geolocation_dataset.csv tidak diunggah ke GitHub karena ukurannya melebihi batas maksimal. Namun, file tersebut telah disertakan dalam versi ZIP sehingga proyek tetap dapat dijalankan secara lokal.**

**Pada file dashboard.py:**
- Versi GitHub menggunakan data dari link (raw GitHub)
- Versi ZIP menggunakan file lokal (main_data.csv)

**Hal ini bertujuan agar dashboard dapat berjalan baik secara online maupun offline.**

## Disclaimer penggunaan AI : 
Pada penyelesaian proyek ini saya menggunakan AI Gemini untuk membantu saya jika terdapat eror di codingan, dan membantu saya dalam memilih kalimat agar proyek ini mudah di pahami.
