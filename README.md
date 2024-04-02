# StudyAlgoritma
nama = str(input("Masukan nama :"))
jadwal = str(input("Masukan jadwal"))
hari = str(input("Masukan hari"))
tugas = str(input("Masukan tugas"))
alamat = str(input("Masukan alamat"))
umur = str(input("Masukan umur"))

print([nama,jadwal,hari])
print(["tugas"])

if tugas <= 7 and hari <= 5:
  print("MAAF ANDA BISA MENGERJAKAN TUGAS")
else:
  print("SELAMAT ANDA BISA MENGERJAKAN TUGAS")
