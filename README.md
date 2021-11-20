# OnlineSalesBusiness
Analisis 3 Point (Keuntungan per Item, Total Diskon, Total Retur) dari Bisnis Penjualan Online yang dikerjakan secara individu.

## Dataset
Dataset didapatkan dari RevoU berupa Google Sheet (Excel) dengan ukuran (1775x6) dan memiliki penjelasan setiap kolom

<br><b>Produt Type</b>     = Tipe Produk (Ada 18 jenis)</br>
<br><b>Net Quantity</b>    = Banyaknya item barang terjual</br>
<br><b>Gross Sales</b>     = Keuntungan Kotor</br>
<br><b>Discounts</b>       = Harga Diskon</br>
<br><b>Returns</b>         = Biaya Retur</br>
<br><b>Total Net Sales</b> = Keuntungan Bersih</br>

## Preprocessing
1. Drop Missing Value
2. Mengganti bilangan real menjadi 2 digit di belakang koma
3. Validasi nilai Total Net Sales

## Data Aggregation (Grouping)
Data dikelompokkan berdasarkan Product Type (Tipe Produk) nya. Dicari juga banyaknya total keuntungan dan juga banyak item terjual, dengan visualisasi berikut:
![Banyak Item](https://drive.google.com/uc?id=119JIamILH8nDeo62svhkBwTdNy9JvQb9)
![Keuntungan Penjualan](https://drive.google.com/uc?id=1F3IRh3T2Jlbu9ZMs1M1H9UllQPjN0zEX)

Basket, Art & Sculpture, Jewelry merupakan 3 produk yang paling berpengaruh karena ketiganya memiliki banyak item penjualan terbanyak dan keuntungan penjualan terbanyak

## Analisis 3 Point
1. Keuntungan per Item
![KeuntunganPerItem](https://drive.google.com/uc?id=1rERNs-NcWMw1Qf1u8Vk0tqdd3WOzaXC-)
2. Total Diskon
![TotalDiskon](https://drive.google.com/uc?id=1r4AaEj3wrGDuB2e7lNGPWPOAPTtEvts7)
3. Total Retur
![TotalRetur](https://drive.google.com/uc?id=1ew6jZfnQTU-pB7-yDbKC8Qktb38PRG4v)

## Lebih Lanjut
Untuk analisis lebih lanjut dan lengkap dapat dilihat di file Online Sales Business.pptx
