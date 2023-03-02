# start-database

Mulai instance, membaca pfile atau spfile, membaca control file dan membaca datafile. Ini dapat dilakukan dalam mode tidak terbatas, memungkinkan akses ke semua pengguna, atau dalam mode terbatas, memungkinkan akses untuk administrator database saja

=> startup


Pada mode ini oracle database mengakhiri semua pernyataan SQL yang sedang berjalan saat ini, dan memutuskan hubungan semua pengguna. Transaksi yang sedang berjalan akan diakhiri.

=> shutdown immediate
