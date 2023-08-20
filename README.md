# Fuzzy-Logic-Tsukamoto-Method-
Sistem Kontrol Frekuensi Putas Kipas Angin Otomatis.
Tahapan input program
* Jumlah Variable = 4
* variable_speed low : 1000 high : 5000, variable_temperature low : 100 high : 600, variable_frek low : 2000 high : 7000
* Jumlah variabel yang diketahui : 2, Nama variabel : variable_speed, Nilai : 4000, Nama variabel : variable_temperature, Nilai : 300, Variabel yang ditanyakan : variable_frek

Jumlah aturan
* Masukkan jumlah peraturan : 4
* Jika: variable_speed_low, dan: variable_temperature_high, maka: low
* Jika: variable_speed_low, dan: variable_temperature_low, maka: low
* Jika: variable_speed_high, dan: variable_temperature_low, maka: high
* Jika: variable_speed_high, dan: variable_temperature_high, maka: high
