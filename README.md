# Dataset Preparation - Credit Card Dataset

## 1. Informasi Dataset

Dataset yang digunakan dalam tugas Penambangan Data ini adalah Credit Card Dataset yang diperoleh dari Kaggle.

**Sumber dataset:** https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

Dataset ini berisi informasi mengenai perilaku penggunaan kartu kredit pelanggan. Dataset memiliki 8.950 baris data dan 18 kolom, termasuk kolom identitas pelanggan.

## 2. Tujuan Penggunaan Dataset

Dataset ini digunakan untuk mempelajari penerapan metode clustering dalam mengelompokkan pelanggan berdasarkan kemiripan perilaku penggunaan kartu kredit. Pengelompokan ini dapat membantu mengidentifikasi karakteristik pelanggan berdasarkan saldo, aktivitas pembelian, transaksi tunai, dan pembayaran. Pada praktikum penambangan data, dataset ini digunakan untuk mempelajari algoritma K-Means dan K-Medoids.

## 3. Fitur Dataset

Dataset terdiri atas kolom identitas pelanggan dan fitur-fitur yang menggambarkan aktivitas kartu kredit, yaitu:

| Fitur | Keterangan |
|---|---|
| CUST_ID | Identitas pelanggan |
| BALANCE | Saldo kartu kredit pelanggan |
| BALANCE_FREQUENCY | Frekuensi pembaruan saldo |
| PURCHASES | Total pembelian |
| ONEOFF_PURCHASES | Total pembelian sekali transaksi |
| INSTALLMENTS_PURCHASES | Total pembelian secara cicilan |
| CASH_ADVANCE | Total penarikan atau penggunaan uang tunai melalui kartu |
| PURCHASES_FREQUENCY | Frekuensi pembelian |
| ONEOFF_PURCHASES_FREQUENCY | Frekuensi pembelian sekali transaksi |
| PURCHASES_INSTALLMENTS_FREQUENCY | Frekuensi pembelian secara cicilan |
| CASH_ADVANCE_FREQUENCY | Frekuensi penggunaan uang tunai |
| CASH_ADVANCE_TRX | Jumlah transaksi penggunaan uang tunai |
| PURCHASES_TRX | Jumlah transaksi pembelian |
| CREDIT_LIMIT | Batas kredit pelanggan |
| PAYMENTS | Total pembayaran yang dilakukan |
| MINIMUM_PAYMENTS | Jumlah pembayaran minimum |
| PRC_FULL_PAYMENT | Persentase pembayaran penuh |
| TENURE | Lama masa penggunaan layanan kartu kredit |

## 4. Kesimpulan

Credit Card Dataset dapat digunakan untuk mempelajari clustering karena memiliki sejumlah fitur numerik yang menggambarkan perilaku penggunaan kartu kredit pelanggan. Melalui fitur-fitur tersebut, pelanggan dapat dikelompokkan berdasarkan kemiripan karakteristiknya menggunakan metode clustering yang dipelajari dalam praktikum.
