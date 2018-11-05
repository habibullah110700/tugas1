

saya = input ('masukkan berat badan anda (kg)')
rekan = input ('masukkan berat badan rekan anda (kg)')
rekan = int(rekan) # konversi string menjadi integral
saya = int(saya)
saya = int(rekan)
hasil1= int(saya >= rekan)
hasil2= int(rekan >= saya)

if rekan > saya :
	kategori = 'anda lebih ringan (kg) dari rekan anda'

if saya > rekan :
	kategori = 'anda lebih berat (hasil2) kg dari rekan anda'

else:
	kategori1 = 'berat anda sama dengan rekan anda'
	kategori2 = 'berat anda lebih ringan dari rekan anda'

print ('{}'.format(kategori1,kategori2))
