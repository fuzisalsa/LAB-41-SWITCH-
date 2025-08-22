# LAB-41-SWITCH-
Tanggal 22 agustus 2025 

# switch
  Switch adalah perangkat keras jaringan yang berfungsi sebagai pusat transfer data antar perangkat, memungkinkan data dikirim ke perangkat yang dituju secara efisien, terutama dengan bantuan switch chip pada router Mikrotik untuk mempercepat transfer data antar port tanpa membebani CPU. Selain itu, switch juga dapat memiliki sistem operasi khusus seperti SwOS Mikrotik yang mendukung fitur-fitur seperti VLAN, QoS, dan Spanning Tree Protocol, serta berbagai jenis produk Mikrotik seperti CRS dan CSS dengan keunggulan masing-masing. fitur Switch chip di Routerboard, memiliki berbagai jenis Switch chip yang ditanam di Routerboard. Meski sama-sama memiliki fungsi Switch, tetapi masing-masing memiliki satu set fitur yang berbeda. Fitur Switch chip memungkinkan Port ethernet melewatkan data dengan kecepatan selayaknya port Switch biasa atau memungkinkan transfer data antar port bisa mencapai cable speed tanpa membebani processor.
  
Berikut adalah daftar Switch chip dan fitur yang dimiliki: 

![m](b1.PNG)

Berikut daftar Routerboard series dengan Switch chip-nya:

![m](b2.PNG)


# Konfigurasi vlan pada routerboard sebagai switch
1. masuk ke winbox
2. lihat menu switch untuk melihat ether mana yang suport sebagai switch chipset
   serta lihat type nya karen setiap type memiliki fungsi yang berbeda 
3. buatkan bridge untuk melewatkan vlan ke interface.
   pilih menu bridge > tab bridge klik (+)

   
5. masukkan interface mana sajah yang akan masuk ke bridge. ether 1  sebagai interfaace yang terhubung ke router utama yang membawa 2 vlan. ether 2 dan 3 itu interface yang akan membagikan vlan ke client
6. pilih menu bridge > port klik (+)



7. 
