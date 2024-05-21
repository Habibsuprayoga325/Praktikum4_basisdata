## praktikum4


```
Nama    : Habib Suprayoga
NIM     : 312310608
Kelas   : TI.23.A6
Matkul  : Basis Data
Dosen   : Agung Nugroho, S.Kom., M.Kom.
```

## Query Filtering

## membuat table terlebih dahulu

Berikut adalah contoh pembuatan tabel pegawai beserta isinya menggunakan kode SQL:

```sql
CREATE TABLE pegawai (
  idpegawai VARCHAR(10),
  nama_depan VARCHAR(50),
  nama_belakang VARCHAR(50),
  email VARCHAR(100),
  telepon VARCHAR(15),
  tgl_kontrak DATE,
  id_job VARCHAR(10),
  gaji INT,
  tunjangan INT
);

INSERT INTO pegawai (idpegawai, nama_depan, nama_belakang, email, telepon, tgl_kontrak, id_job, gaji, tunjangan) VALUES
("E001", "Ferry", "Gustiawan", "ferry@gmail.com", "07117059004", "2005-09-01", "L001", 2000000, 500000),
("E002", "aris", "ganiardi", "aris@gmail.com", "07117059008", "2006-03-28", "L002", 2000000, 200000),
("E003", "faiz", "ahnad", "faiz@yahoo.com", "07117059234", "2006-10-01", "L003", 1500008, NULL),
("E004", "enna", "bunton", "enna@yahoo.com", "07117059567", "2004-03-19", "10004", 1500000, 9),
("E005", "mike", "Scoof", "mike@gmail.com", "07117059789", "2007-09-01", "L005", 1250000, 9),
("E006", "lincoln", "burrows", "linc@yahoo.com", "07117059789", "2008-09-01", "L006", 1750000, NULL);
```


berikut hasil outputnya :

![Image](ss/ss1.png)
