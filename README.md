## Deskripsi

Proyek ini merupakan DAta Analyst terhadap **Brazilian E-Commerce** yang divisualisasikan melalui sebuah website.

## Sumber Data
Kaggle Dataset brazilian-ecommerce [(Link Download)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

## Struktur Direktori

- **/data**: Merupakan Direktori Projek yang terdiri atas dataset yang berformat .csv
- **/dashboad**: Terdiri atas file main.py dan function.py yang merupakan kode utama dalam pembuatan visualisasi website
- **notebook.ipynb**: File yang digunakan untuk melakukan analisis data.

## Instalasi

1. Clone repository ke komputer lokal anda menggunakan perintah berikut:

   ```shell
   git clone https://github.com/RafiyatnSandya/Test.git
   ```
2. Lakukan Instalasi Kaggle dan Konfigurasi Kaggle Api:
   dengan cara sebagai berikut :
   
   [Kaggle Installation and API configuration](https://github.com/Kaggle/kaggle-api)
   
4. Lakukan Instalasi Library Dengan Perintah Berikut:

    ```shell
    pip install streamlit numpy seaborn pandas matplotlib zipfile unidecode
    
    ```

## Penggunaan
1. Melakukan Akses dan Kompilasi(Local):

    ```shell
    cd dashboard
    streamlit run main.py
    ```
2. Melakukan Akses secara Cloud (online):
   [Project Data Analytics](https://dicoding1.streamlit.app/)