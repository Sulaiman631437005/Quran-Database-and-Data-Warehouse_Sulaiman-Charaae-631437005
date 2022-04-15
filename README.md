# Quran-Database-and-Data-Warehouse_Sulaiman-Charaae
This project is  part of Big data and data warehouse course.  Which is managing data in database by using Olap-cube and postgreSql database program.
Usability, The data set consists of Ayah Quran,transliteration and language translation in ASEAN countries. Due to the difficult retrieve data quote obstacles. That's causing us get some data for Asian languages. which consists of data in Thai, English, Malay, Indonesian and Cambodian language which has the extension csv file.csv

# Tool 
- Github
- Postgresql 
- Excel 
- Visual Studio Code

# Step to do star schema 
take table arabic to be main and take table quran_surah transliteration and translate by using statement join

- 1.Create table arabic consist column index, surah,ayah and text.
quran_surah consist column surah_id,arabic,latin, english,sajda,ayah,types.
 transliteration consist column index,surah,ayah and transillumination and 
translate consist  column index,surah,ayah,th_translate,en_translate,mal_translate,
id_translate,kh_translate.
- 2.Choose table arabic to main table and selected column arabic.surah,quran_surah.arabic,quran_surah.latin,arabic.ayah,arabic.text, 
transliteration.transliteration,translate.th_translate,translate.en_translate,translate.mal_translate,translate.id_translate,translate.kh_translate for display
- 3.Join table quran_surah into table arabic by using arabic.surah = quran_surah.surah_id
- 4.join table transliteration into table arabic.index = transliteration.index

# Step to do data analysis
- :point_right: 1.Collected data from various sources.
- :point_right: 2.Analyze data perform analysis and synthesis of data what we having data.
- :point_right: 3.Insert data to postgresql by using file.csv
- :point_right: 4.Create question that we need to know that are about quran.
   - 1.How many verses(ayah) are there in Al-quran?
   - 2.How many verses(ayah) each surah are there in the Quran?
   - 3.How many sujud sujdah are there in al-quran?
   - 4.Which surah are there sujud sajdah and which sequence verse?
   - 5.How many surah have no sujud sajdah?
   - 6.Which surah that begin with alif lam meem?  
   - 7.How many surah that begin with alif lam meem?
   - 8.How many surah there are verses(ayah) more than 200 verses?
   - 9.Which surah are there verses(ayah)more than 200 verses?
   - 10.How many surah there are verses(ayah)less than 10 or equal to 10?
   - 11.Which surah there are verses(ayah)less than 10 verses or equal to 10 verse?
   - 12.from the holy qur-an ,how many verses(ayah) for the surah that shortest and the longest?
- :point_right: 5.Retrieve data from  database by using select statement
- :point_right: 6.Check result 

# Authors   
- 1.Sulaiman Charaae 631437005 
- 2.Amir Radeng 631437011
- 3.Huda Yala 632437002

# Summary
The project Which is managing data in database to do data analysis with star schema and various tool for getting result 

# Reference
- hablullah, A. (2021) data-quran.: Live Science [online]. Available at: https://github.com/hablullah/data-quran?fbclid=IwAR0WhiCADjUujY-Q2pzOvNF3A-rCwv2ZibvgQFC9AzSfR5XEryZiPLtIpHw [Accessed 15th April 2022]. 

- voiceofquran, A. (2013) Quran-Surah.Toranto,Canada: Live Science [online]. Available at: https://github.com/voiceofquran/Quran-Surah?fbclid=IwAR39NZOCNp0U8o0VwQZMIh3qRJVVHwbRxoJM5YcH0HaYyox7h2jXXuay6uY
[Accessed 15th April 2022]. 


