# Tugas Akhir Visualisasi Data dan Wrangling Pacmann
Di bawah ini adalah hasil dan penjelasan dari proyek Visualisasi Data dan Wrangling yang disediakan oleh tukang pos. Proyek ini mencakup analisis dan pengolahan data yang diambil dari situs Kaggle. Proyek ini bukan proyek individu, jadi saya bekerja sama dengan teman saya,Bersama AKbar Maulana untuk mengerjakan proyek ini. Dataset yang digunakan adalah data tingkat bunuh diri dan kondisi sosial ekonomi dari tahun 1990 hingga 2022.


# A. Backgroud Problem 
Masalah bunuh diri adalah masalah kesehatan masyarakat yang kompleks dengan berbagai aspek yang berdampak pada masyarakat di seluruh dunia. Hal ini tidak semata-mata disebabkan oleh kondisi kesehatan mental individu, tetapi secara signifikan dipengaruhi oleh faktor sosial, ekonomi, dan demografi. Memahami pola dan korelasi bunuh diri dapat membantu mengembangkan strategi pencegahan yang efektif. Mengingat bahwa dataset ini menyertakan indikator ekonomi di samping tingkat bunuh diri, hal ini mengindikasikan adanya ketertarikan untuk mengeksplorasi bagaimana faktor-faktor ekonomi ini berkorelasi dengan kejadian bunuh diri di berbagai demografi dan dari waktu ke waktu.

# B. Objective
1. Menganalisis data bunuh diri dari periode 1990 hingga 2022 untuk mengidentifikasi tren dan pola yang terkait dengan lonjakan angka bunuh diri.
2. Menyelidiki faktor-faktor yang dapat memicu peningkatan angka bunuh diri, terutama berdasarkan faktor sosioekonomi.
3. Memahami hubungan antara faktor-faktor yang berkontribusi terhadap tingginya angka bunuh diri.
4. Mengembangkan solusi dan rekomendasi yang bertujuan untuk mengurangi angka bunuh diri.


# C. Goals
Untuk mengeksplorasi hubungan antara tingkat bunuh diri dengan kondisi sosial ekonomi dan faktor demografi lainnya, dan kemudian menilai secara lebih rinci interaksi antara penyebab-penyebab tersebut. Tujuan jangka panjangnya adalah untuk menghasilkan rekomendasi kebijakan dan intervensi yang dapat membantu mencegah bunuh diri.


# D. Work flow
Alur kerja dalam proyek ini adalah:

    - 1. Finding dataset 
    - 2. Dataset cleaning which includes:
        * Rename values
        * Remove duplicated data
        * Checking unknown values of categorical data 
        * Deleting unnecessary columns
        * Checking missing values on each column
        * Deleting missing values on SuicideCount, InflationRate, and EmploymentPopulationRatio column. Reason to delete rather than using imputation is to avoid bias as much as possible
        * Handling missing values on GDP, GDPPerCapita, GrossNationalIncome, and GNIPerCapita columns using median due to the data distribution is skewed     
    - 3. Save and download cleaned dataset
    - 4. Visualization with tableau
    - 5. Data analytics to gain insight and give recommendation 
    - 6. Creating dashboard and report


# E. File Description
1. Modul 'code_cleansing.ipynb' adalah sebuah program yang digunakan untuk melakukan pembersihan data.
2. File 'suicide_rates_1990-2022.csv' adalah set data yang digunakan untuk proses pembersihan.
3. File 'cleaned_suicide_rates_1990-2022.csv' adalah dataset yang telah dibersihkan yang akan digunakan untuk visualisasi dan analisis.

# F. Link 
1. Link dataset: https      : //www.kaggle.com/datasets/ronaldonyango/global-suicide-rates-1990-to-2022/data
2. Link VIdio Presentasi    : https://www.youtube.com/watch?v=XaPU-w6oP8c
3. Link Tableau: https      ://public.tableau.com/app/profile/ahmad.fauzan7259/viz/Visualisasi_Project_Pacman/Dashboard1
4. Link Medium Ahmad Fauzan : https://medium.com/@fauzanediting02/analisis-tingkat-bunuh-diri-faktor-ekonomi-1990-2022-7746d4b96cb7
5. Link Mediun Akbar Maulana : https://medium.com/@akbarmaulana_/analysis-on-suicide-rates-economic-factors-1990-2022-aff7ac87d7bc
6. Linkedin Ahmad Fauzan: https://www.linkedin.com/in/akbar-maulana--/
7. Linkedin Akbar Maulana    : https://www.linkedin.com/in/akbar-maulana--/
8. Link Github Akbar Maulana :https://github.com/maschenyy/Pacmann_Data_Visualization_Wrangling/tree/main?tab=readme-ov-file
