# PI-SERVER-to-Python

LANGKAH 1. Pastikan API yang dibutuhkan

PI System memiliki API seperti PI Web API yang memungkinkan anda berkomunikasi dengan PI Data Archive menggunakan HTTP/Rest. Pastikan PI WEB API sudah diaktifkan di server anda.

LANGKAH 2. Install Modul HTTP untuk python

Gunakan modul seperti request atau modul lain untuk berkomunikasi dengan PI Web API. anda bisa menginstalnya dengan perintah beriktu:

    pip install requests

LANGKAH 3. Sambungkan Python dengan PI WEB API

Gunakan API ini untuk membaca data dari PI DATA ARCHIVE:

    import requests
    import json
    # URL dari PI Web API (gantikan dengan PI_WEB_API_URL ="https://"
