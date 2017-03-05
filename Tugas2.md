## Tugas-02 (27/02/2017):

1. Buatlah program untuk menampilkan daftar kode ASCII
2. Buat catatan tentang berbagai macam fungsi matematik yang terdapat dalam module "math"

## Penyelesaian :
  1. Program untuk menampilkan daftar kode ASCI

  ```python
  print "				TABEL CODE ASCII"
  print "========================================================================="
  print "|Decimal		|Hexadecimal		|character		|"
  print "========================================================================="
  for a in range (256):
    print a, "			|", hex(int(a)), "			|", chr(int(a)), "			|"
  print "========================================================================="
  ```
