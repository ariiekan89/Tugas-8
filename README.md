Langkah Penguncian Table: MariaDB [ariyanto_311810886]> lock table operator write;
Langkah Backup Table: MariaDB [ariyanto_311810886]> select * into outfile 'b_operator' from operator;
MariaDB [ariyanto_311810886]> delete from operator;
MariaDB [ariyanto_311810886]> select * from operator;
Langkah Load Data Infile Table: MariaDB [ariyanto_311810886]> select * into outfile 'b_operator' from operator;
![image](https://user-images.githubusercontent.com/85496876/122761364-5c5eb400-d2c6-11eb-933f-f3dc7db5316a.png)
Langkah Backup & Restore menggunakan MYSQLDUMP: 
![Uploading image.png…]()
