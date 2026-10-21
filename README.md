class Hewan:
  def __init__(self, nama):
    self.nama = nama

  def bersuara(self):
    print(f"{self.nama} mengeluarkan suara umum hewan.")

class Kambing(Hewan):
  def __init__(self, nama, warna):
    super().__init__(nama)
    self.warna = warna

  def bersuara(self):
    print(f"{self.nama} bilang: Mbekk")

  def info_tambahan(self):
    print(f"{self.nama} adalah kambing berwarna {self.warna}.")
  
