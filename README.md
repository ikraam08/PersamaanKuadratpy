
## Pembuatan Tugas dita

````shell
Nama   : Ikram Ramadhan
for    : Tugas dita
````


### 1. PersamaanKuadrat.py
* *CODINGAN FILE 1

```python
import cmath as cm

print("Bentuk Persamaan Kuadrat : ax^2+bx+c= 0")

# Pengimputan
a = float(input ("a = "))
b = float(input ("b = "))
c = float(input ("c = "))

# Mengecek nilai a = ?
if a==0 :
    print("Nilai Tidak boleh 0!")
else :
    D = b** 2 -4*a*c
    # Mengecek Nilai Diskriminan
    if D>0:
        x1 = (-b+cm.sqrt(D))/(2*a)
        x2 = (-b-cm.sqrt(D))/(2*a)
        print("jenis Akarnya 2 Akarnya Berbeda Dan Real")
    elif D==0 :
        x1 =(-b/(2*a))
        x2 =(-b/(2*a))
        print("Jenis Akarnya Adalah 2 Yang Sama Dan Sama Dan Real")
    else :
        x1 = (-b+cm.sqrt(D))/(2*a)
        x2 = (-b+cm.sqrt(D))/(2*a)
        print("jenis Akarnya 2 Akarnya Berbeda Dan Imajiner")
print("akar dari Persamaan kuadrat adalah" +str(x1)+" dan "+str(x2))
print("Deskriminan\t:",D)



```

