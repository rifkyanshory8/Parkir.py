def simulasi_parkir_kendaraan_bermotor():
    def enqueue(parkir,x):
        parkir.tambahkan(x)
    
    def dequeue(parkir):
        jika len(parkir) > 0:
            kembali parkir.pop(0)
        kalau tidak:
            kembalikan "Parkir kosong"
    
    parkir = []

    untuk saya dalam jangkauan (5):
        x = input("Masukkan kendaraan bermotor : ")
        enqueue(parkir, x)
        print("Parkir saat ini :", parkir)
    
    print("Mulai dequeue kendaraan bermotor:")
    untuk saya dalam jangkauan (5):
        print("Dequeue kendaraan bermotor : ",dequeue(parkir))
        print("Parkir saat ini :", parkir)

simulasi_parkir_kendaraan_bermotor()
