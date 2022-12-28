## 🚀 About Me

Nama : Ricky Sambora<br>
NIM : 4.31.20.1.21<br>
Kelas : TE-3B

# Jobsheet 3 Topologi Jaringan Lokal dan WiFi

Pada jobsheet 3 terdapat 5 project yaitu scanning WiFi, WiFi station, WiFi auto-reconnect, hostname WiFi, dan mengirim data sensor ke database.

### Alat dan Bahan

-   ESP32
-   Arduino IDE (Terinstal ESP32)
-   Library DHT dan Adafruit unified sensor
-   Breadboard
-   Kabel Jumper
-   Resistor < 220Ω
-   LED
-   Sensor DHT

### Instalasi ESP-32

1. Buka Arduino IDE
    - Masuk ke **Preferences**
    - Isikan board url dengan link : https://dl.espressif.com/dl/package_esp32_index.json dan simpan
    - Buka **Tools** > **Board** > **Boards Manager**
    - Cari ESP32, by Espressif. Kemudian instal
    - Pilih flash mode DIO/QIU menyesuaikan
2. Jalankan program .ino
3. Jika terdapat error saat uploading, tekan dan tahan tombol _Boot_ pada ESP32 saat upload, hingga _Connecting_ selesai

Nb. Proses instalasi dapat dilewati jika Arduino IDE sudah terintegrasi dengan ESP32.
Atau download `libraries` dan upload pada direktori projek.

### Instalasi DHT & Adafruit Libraries

1. Buka Arduino IDE
2. Buka **Sketch** > **Include Library** > **Library Manager**
3. Cari **DHT sensor library** by Adafruit. Kemudian instal.
    - Atau dapat melalui link [DHT Library](https://github.com/adafruit/DHT-sensor-library) dan upload pada libraries di direktori projek. Rename direktori menjadi **DHT_sensor_library**.
4. Instal juga library **Adafruit unified sensor** by Adafruit
    - Atau dapat melalui link [Adafruit Sensor](https://github.com/adafruit/Adafruit_Sensor) dan upload pada libraries di direktori projek. Rename direktori menjadi **Adafruit_Unified_Sensor**.

Nb. Proses instalasi dapat dilewati jika libraries telah diinstal.
Atau download `libraries` dan upload pada direktori projek.

## Project A - WiFi Modes and Scanning

### Keluaran

<img src="https://user-images.githubusercontent.com/49542850/209751678-d4ecb7f4-fd5e-45da-9896-5907d4c60878.png" width="600px">

### Penjelasan

Wifi melakukan scanning.

## Project B - Menghubungkan ESP32 dengan jaringan WiFi (station mode)

### Keluaran

<img src="https://user-images.githubusercontent.com/49542850/209751686-633fa28c-7613-41eb-8faf-0c9a9c9a6895.png" width="600px">

### Penjelasan

Wifi sebagai station (client).

## Project C - Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi

### Keluaran

<img src="https://user-images.githubusercontent.com/49542850/209751687-e587400d-f344-44f2-9af5-bb3d57ce774a.png" width="600px">

### Penjelasan

Wifi auto terhubung kembali saat putus.

## Project D - Mengganti Hostname ESP32

### Keluaran

<img src="https://user-images.githubusercontent.com/49542850/209751688-e2743c94-5c77-405e-aedf-d990f45fa9d2.jpeg" width="600px">

### Penjelasan

Identitas ESP32 diganti.

## Project E - Mengirim Data Sensor ke Database

### Keluaran

<img src="https://user-images.githubusercontent.com/49542850/209751690-5897da3c-f8aa-4e34-90ed-a9ca76194402.png" width="600px">

<img src="https://user-images.githubusercontent.com/49542850/209751694-7465347a-596b-48b6-88a8-8efaabae92a9.png" width="600px">

### Penjelasan

Data sensor dikirim ke web.
