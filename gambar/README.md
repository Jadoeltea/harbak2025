# Folder Gambar Pertandingan

Struktur folder untuk gambar pertandingan:

```
gambar/
├── tenis meja/
│   ├── detailtenismeja.png
│   └── jadwalpertandingantenismeja.png
├── badminton/
│   ├── detailbadminton.png
│   └── jadwalpertandinganbadminton.png
├── tenis lapang/
│   ├── detailtenislapang.png
│   └── jadwalpertandingantenislapang.png
├── voli putera/
│   ├── detailvoliputera.png
│   └── jadwalpertandinganvoliputera.png
├── voli puteri/
│   ├── detailvoliputeri.png
│   └── jadwalpertandinganvoliputeri.png
├── billiard/
│   ├── detailbilliard.png
│   └── jadwalpertandinganbilliard.png
├── basket putera/
│   ├── detailbasketputera.png
│   └── jadwalpertandinganbasketputera.png
├── basket puteri/
│   ├── detailbasketputeri.png
│   └── jadwalpertandinganbasketputeri.png
├── futsal putera/
│   ├── detailfutsalputera.png
│   └── jadwalpertandinganfutsalputera.png
├── futsal puteri/
│   ├── detailfutsalputeri.png
│   └── jadwalpertandinganfutsalputeri.png
├── sepak bola 45/
│   ├── detailsepakbola45.png
│   └── jadwalpertandingansepakbola45.png
└── mini soccer/
    ├── detailminisoccer.png
    └── jadwalpertandinganminisoccer.png
```

## Cara Kerja

### Tombol "Detail"
1. Mencari gambar di path: `gambar/{cabang-olahraga}/detail{cabang-olahraga}.png`
2. Contoh untuk Tenis Meja: `gambar/tenis meja/detailtenismeja.png`
3. Menampilkan gambar detail pertandingan (drawing/bagan turnamen)

### Tombol "Preview Jadwal"
1. Mencari gambar di path: `gambar/{cabang-olahraga}/jadwalpertandingan{cabang-olahraga}.png`
2. Contoh untuk Tenis Meja: `gambar/tenis meja/jadwalpertandingantenismeja.png`
3. Menampilkan gambar jadwal pertandingan

## Format Gambar

- **Format**: PNG
- **Ukuran**: Disarankan 800x600 pixel atau lebih besar
- **Detail**: Pattern `detail{cabang-olahraga}.png`
- **Jadwal**: Pattern `jadwalpertandingan{cabang-olahraga}.png`

## Cabang Olahraga

1. **Tenis Meja** → Detail: `detailtenismeja.png`, Jadwal: `jadwalpertandingantenismeja.png`
2. **Badminton** → Detail: `detailbadminton.png`, Jadwal: `jadwalpertandinganbadminton.png`
3. **Tenis Lapang** → Detail: `detailtenislapang.png`, Jadwal: `jadwalpertandingantenislapang.png`
4. **Voli Putera** → Detail: `detailvoliputera.png`, Jadwal: `jadwalpertandinganvoliputera.png`
5. **Voli Puteri** → Detail: `detailvoliputeri.png`, Jadwal: `jadwalpertandinganvoliputeri.png`
6. **Billiard** → Detail: `detailbilliard.png`, Jadwal: `jadwalpertandinganbilliard.png`
7. **Basket Putera** → Detail: `detailbasketputera.png`, Jadwal: `jadwalpertandinganbasketputera.png`
8. **Basket Puteri** → Detail: `detailbasketputeri.png`, Jadwal: `jadwalpertandinganbasketputeri.png`
9. **Futsal Putera** → Detail: `detailfutsalputera.png`, Jadwal: `jadwalpertandinganfutsalputera.png`
10. **Futsal Puteri** → Detail: `detailfutsalputeri.png`, Jadwal: `jadwalpertandinganfutsalputeri.png`
11. **Sepak Bola 45+** → Detail: `detailsepakbola45.png`, Jadwal: `jadwalpertandingansepakbola45.png`
12. **Mini Soccer** → Detail: `detailminisoccer.png`, Jadwal: `jadwalpertandinganminisoccer.png` 