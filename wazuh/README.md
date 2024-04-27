# Introduction Wazuh

Mungkin ada yang belum tahu apa itu Wazuh. Ini adalah platform open source untuk deteksi ancaman dan pemantauan keamanan, yang merupakan implementasi dari SIEM. Wazuh memiliki lebih banyak fitur dibandingkan dengan aplikasi serupa. Sebagai SIEM, Wazuh menggabungkan dan menganalisis data secara real-time dari berbagai sumber untuk deteksi ancaman dan kepatuhan. Sebagai XDR, Wazuh menawarkan solusi keamanan yang komprehensif untuk deteksi, analisis, dan respons terhadap ancaman di berbagai lapisan infrastruktur TI. Wazuh mengumpulkan data dari berbagai sumber untuk pemantauan keamanan terpadu. Selain itu, saya melakukan mengintegrasikan Wazuh dengan MISP, The Hive, Cortex Analysis, dll.
Wazuh adalah platform keamanan yang komprehensif dan tangguh, dirancang untuk melindungi infrastruktur IT Anda dari ancaman cyber. Dengan kombinasi yang kuat dari deteksi ancaman real-time, analisis log, dan manajemen keamanan, Wazuh membantu organisasi mempertahankan keamanan mereka dengan efektif dan efisien.
wazuh juga merupakan platform monitoring keamanan open source yang bisa menyatukan kemampuan XDR dan SIEM. yang bisa digunakan untuk melindungi host endpoint on-premises, virtualisasi, container, dan berbasis cloud.
Wazuh membantu organisasi atau individu untuk melindungi aset data mereka dari ancaman. dan ini banyak digunakan oleh ribuan organisasi di seluruh dunia, dari usaha kecil hingga perusahaan besar. 

![image](https://github.com/Adimuhlil401/Securiity-engineer/assets/19413742/bee62683-5d2a-4fd0-8e23-d2df9e4fc411)

# Component
Komponen wazuh terbagi ke beberapa bagian yang memiliki based wazuh agent, dan 3 komponen utama yaitu : wazuh server, wazuh indexer, dan wazuh dashboard.

•  Wazuh Indexer

Wazuh Indexer Adalah Server yang digunakan untuk menganalisis dan full-text search, komponen pusat indexer ini untuk mengindex dan menyimpan alert yang di generate oleh wazuh server.
 

•  Wazuh Server

Wazuh Server Adalah Server untuk menganalisis data yang diterima dari agent, ia akan memprosesnya melalui rule dan decoder, menggunakan threat inteligence untuk mencari indicators of compromise (IOCs) yang terkenal. sebuah server dapat menganalisis data dari ratusan atau ribuan agent, dan melakukan penskalaan secara horizontal ketika di set up sebagai sebuah cluster. dan kompenen utama ini juga digunakan untuk mengelola agent, mengkonfigurasi dan upgrade dari jarak jauh jika diperlukan.
 

•  Wazuh Dashboard

Wazuh Dashboard adalah tampilan antar muka atau GUI dari wazuh untuk visualisasi dan analisis data. dashboard ini mencakup dashboard untuk event security, regulatory compliance (e.g., PCI DSS, GDPR, CIS, HIPAA, NIST 800-53), detected vulnerable applications, file integrity monitoring data, configuration assessment results, cloud infrastructure monitoring events, dan yang lainnya. dashboard ini juga dapat digunakan untuk mengelola konfigurasi wazuh dan memantau statusnya.


•  Wazuh Agent

Wazuh agent ini merupakan aplikasi yang di install pada endpoint seperti laptop, server, desktop, cloud instances atau virtual machines. agent yang diinstall menyediakan kemampuan pencegahan, deteksi dan respon ancaman. yang bisa berjalan pada sistem operasi seperti linux, windows, macOS, solaris, AIX, dan HP-UX.


Selain wazuh bisa memantau berbasis Agent ia juga bisa dapat memantau perangkat tanpa agent seperti Firewall, Switch, Router, atau Network IDS, dll. misalnya data log sistem dapat dikumpulkan melalui SYslog, dan konfigurasinya dapat dipantau melalui pemeriksaan data secara berkala mengunakan SSH atau API.

Adapun Diagram dibawah ini bisa mewakili komponen Wazuh dan data flow.

![image](https://github.com/Adimuhlil401/Securiity-engineer/assets/19413742/0cc76dbb-c6e8-42a6-afe3-86c5676cd6a9)



# Arsitektur Wazuh 
















# Referensi

https://documentation.wazuh.com/

