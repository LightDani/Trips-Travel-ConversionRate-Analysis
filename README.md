# Trips and Travel Conversion Rate Analysis
> Repository ini dibuat untuk memenuhi Final Project Data Science Rakamin Batch 35<br>
> 
> A Final Poject by Data Busters

### Anggota Kelompok:
1. Aryo Wicaksono
2. Dwi Cahya Nur Faizi
3. Karissa Triastari
4. Raden Treva Raka Putra
5. Tiolan Sweter Simanjuntak
6. Wahyu Endranaka

Dataset: [Holiday Package Purchase Prediction](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction)

## Data Understanding
### Problem:
Perusahaan 'Trips & Travel.Com' menawarkan lima jenis produk kepada pelanggan mereka, yaitu Paket Basic, Standard, Deluxe, Super Deluxe, dan King. Namun, berdasarkan data tahun lalu, terlihat tingkat konversi yang rendah, dimana hanya 18% dari pelanggan yang membeli paket yang ditawarkan. Perusahaan belum memanfaatkan informasi yang tersedia dari pelanggan dalam menawarkan produk dan menghubungi pelanggan secara  acak, sehingga biaya marketing menjadi tidak efisien.

### Goal:
Dalam usaha ekspansi user base, perusahaan "Trips & Travel.Com" berencana menawarkan produk baru yaitu Wellness Tourism Package. Dalam meluncurkan produk baru, perusahaan ingin:
* Meningkatkan conversion rate dari penawaran produk baru tersebut.
* Membuat biaya marketing menjadi lebih efisien.

### Objectives:
* Membuat model yang dapat memprediksi pelanggan yang berpotensi membeli paket baru.
* Mengidentifikasi segmentasi pelanggan yang berpotensi membeli produk baru berdasarkan atribut mereka.

### Business Metrics:
* Conversion Rate: Persentase dari pelanggan yang ditawarkan yang akhirnya membeli produk tersebut.
* ROI (Return on Investment): Rasio dari nilai keuntungan terhadap biaya marketing.

Metadata
| Column | Description |
| --- | --- |
| CustomerID | Unique customer ID |
| ProdTaken | Target variable, Whether customer has taken the product or not |
| Age | Age of customer |
| TypeofContact | How customer was contacted (Company Invited or Self Inquiry) |
| CityTier | City tier depends on the development of a city, population, facilities, and living standards. The categories are  |ordered i.e. Tier 1 > Tier 2 > Tier 3
| DurationOfPitch | Duration of the pitch by a salesperson to the customer |
| Occupation | Occupation of customer |
| Gender | Gender of customer |
| NumberOfPersonVisiting | Total number of persons planning to take the trip with the customer |
| NumberOfFollowups | Total number of follow-ups has been done by the salesperson after the sales pitch |
| ProductPitched | Product pitched by the salesperson |
| PreferredPropertyStar | Preferred hotel property rating by customer |
| MaritalStatus | Marital status of customer |
| NumberOfTrips | Average number of trips in a year by customer |
| Passport | The customer has a passport or not (0: No, 1: Yes) |
| PitchSatisfactionScore | Sales pitch satisfaction score |
| OwnCar | Whether the customers own a car or not (0: No, 1: Yes) |
| NumberOfChildrenVisiting | otal number of children with age less than 5 planning to take the trip with the customer |
| Designation | Designation of the customer in the current organization |
| MonthlyIncome | Gross monthly income of the customer |