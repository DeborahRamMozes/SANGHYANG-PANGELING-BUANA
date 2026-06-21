# Sanghyang Pangeling Buana

**Sanghyang Pangeling Buana** nyaéta repo pikeun nyusun, maca, jeung ngajaga kaweruh Sunda Buhun kalayan puseur kana **Buana, Kala, Wanci, Kabuyutan, Karuhun, Lemah Cai, Sabda, Bayu, Hedap, Rasa, jeung Laku**.

Repo ieu henteu ngajadikeun Sunda Buhun minangka bahan hiasan atawa objék tina kaca panon luar. Sunda Buhun dipaké minangka **puseur maca hirup, lemah cai, karuhun, kabuyutan, jeung wanci**.

---

## Puseur Repo

Repo ieu dipaké pikeun:

- nyusun **Pustaka Hirup** Sunda Buhun;
- ngumpulkeun catetan sumber anu bisa dipariksa;
- nyieun glosarium istilah Sunda Buhun;
- nyusun catetan arsip pikeun naskah, ritual, kecap, istilah, gambar, jeung sumber adat;
- ngajaga pangucap suci sangkan henteu dipalsukeun;
- maca Kala Sunda, Wanci, Usum, Pare, Cai, Gunung, jeung Leuweung;
- ngajelaskeun laku sapopoé dumasar kana Sabda, Bayu, Hedap, Rasa, jeung Eling.

---

## Kecap Konci

**Sanghyang · Buana · Karesian · Kabuyutan · Karuhun · Lemah Cai · Kala · Wanci · Laku · Riksa · Tapa · Eling · Pangeling · Sabda · Bayu · Hedap · Rasa · Hirup · Hurip · Pare · Cai · Gunung · Leuweung · Sunda · Siksa · Guru · Darma · Hayu**

---

## Pustaka Hirup

Pustaka Hirup dibagi jadi dua:

### 1. Pustaka Jero

Pustaka Jero nyaéta sumber anu geus diasupkeun jeung diriksa dina repo ieu, saperti:

- naskah;
- transliterasi;
- buku;
- jurnal;
- arsip museum;
- catetan adat;
- glosarium Sunda Buhun;
- kalénder Sunda;
- pangucap suci anu boga sumber écés.

### 2. Pustaka Luar

Pustaka Luar nyaéta sumber anu aya di luar repo jeung kudu bisa dipariksa deui, saperti:

- Perpusnas / Khastara;
- Leiden / KITLV / UBL;
- Kabuyutan Ciburuy;
- museum;
- jurnal;
- buku;
- GitHub;
- Google Drive;
- database;
- website arsip;
- catetan panalungtikan.

---

## Panyaring Sumber

Unggal kaweruh kudu dibéré tanda kapastian.

| Tanda | Harti |
|---|---|
| A | Naskah langsung atawa arsip utama |
| B | Catetan arsip atawa museum |
| C | Tafsir jurnal atawa buku |
| D | Catetan adat hirup anu kacatet |
| E | Rekonstruksi modéren |
| F | Kosmologi artistik atawa catetan pribadi |
| X | Can diverifikasi / teu aya sumber écés |

Lamun tingkatna **X**, tuliskeun:

> Ieu can tiasa ditarima minangka kaweruh Sunda Buhun sabab sumberna teu acan écés.

---

## Panyaring Pangucap Suci

Repo ieu henteu meunang nyieun doa, mantra, kidung, liturgi, atawa pangucap karuhun palsu.

Lamun aya pangucap kuna, kudu dicatet ku format:

```text
Judul pangucap:
Sumber:
Naskah / arsip:
Basa:
Aksara:
Transliterasi:
Tarjamahan Sunda kiwari:
Harti dina Sunda Buhun:
Pamakéan:
Watesan:
Tingkat kapastian:
```

Lamun sumberna teu kapanggih, tuliskeun:

> Teu acan kapanggih sumber pangucap kuna anu tiasa dipastikeun.

Lamun perlu nyieun ungkara anyar, kudu dilabélan écés:

> Pangucap anyar, sanés pangucap kuna.

---

## Catetan Arsip

Unggal istilah, ritual, naskah, gambar, atawa sumber anyar kudu dicatet ku format:

```text
Judul:
Jenis Sumber:
Asal:
Pangarang / Penyusun:
Taun:
Tempat Arsip:
Tumbu / Nomor Katalog:
Basa / Aksara:
Kecap Konci:
Eusi Pokok:
Patali jeung Buana:
Patali jeung Karesian:
Patali jeung Kala / Wanci:
Patali jeung Kabuyutan:
Patali jeung Karuhun:
Status Verifikasi:
Catetan:
Rekomendasi:
```

Rekomendasi dieusian ku salah sahiji:

- diasupkeun ka Pustaka Jero;
- disimpen ka Pustaka Luar;
- ditunda;
- ditolak.

---

## Rarancang Folder

```text
.
├── README.md
├── pustaka-jero/
├── pustaka-luar/
├── catetan-arsip/
├── glosarium/
├── kala-wanci/
├── pangucap-suci/
├── riksa-sumber/
├── seni-buana/
└── docs/
```

### `pustaka-jero/`

Eusina sumber anu geus diberesihan jeung diverifikasi.

### `pustaka-luar/`

Eusina daptar tumbu, katalog, atawa catetan sumber anu kudu dipariksa deui.

### `catetan-arsip/`

Eusina catetan arsip pikeun istilah, ritual, naskah, gambar, jeung sumber anyar.

### `glosarium/`

Eusina istilah Sunda Buhun jeung hartina dina pancer Buana, Wanci, Laku, Kabuyutan, jeung Karuhun.

### `kala-wanci/`

Eusina catetan ngeunaan Kala Sunda, Wanci, Usum, Saka Sunda / Caka Sunda, Parocaang, Paropoek, cai, pare, jeung leuweung.

### `pangucap-suci/`

Eusina ngan pangucap anu boga sumber jelas. Pangucap anyar kudu dipisahkeun jeung dilabélan minangka pangucap anyar.

### `riksa-sumber/`

Eusina panyaringan sumber, tingkat kapastian, jeung catetan verifikasi.

### `seni-buana/`

Eusina maca karya seni dumasar kana Buana, Rasa, Karuhun, Lemah Cai, warna, garis, raga, jeung lapisan.

---

## Tata Nambahkeun Sumber

Saméméh nambahkeun sumber anyar:

1. pastikeun asal sumberna;
2. catet pangarang atawa panyusunna;
3. catet tempat arsip, katalog, atawa tumbuna;
4. tandaan tingkat kapastian A/B/C/D/E/F/X;
5. ulah ngaku sumber kuna lamun can diverifikasi;
6. simpen heula minangka Pustaka Luar lamun can pasti;
7. pindahkeun ka Pustaka Jero lamun geus beres diverifikasi.

---

## Watesan

Repo ieu henteu ngaganti kokolot adat, ahli naskah, filolog, atawa pangjaga kabuyutan.

Repo ieu ngan jadi **pancer catetan, pangeling, jeung panyaring sumber** sangkan kaweruh Sunda Buhun henteu kacampur ku klaim palsu.

---

## Pangeling

Sunda Buhun lain objék.

Sunda Buhun nyaéta kaca panon.

Sunda Buhun nyaéta tata maca buana.

Sunda Buhun nyaéta pangeling ka asal.

Sunda Buhun nyaéta laku pikeun ngajaga hirup, lemah cai, karuhun, jeung mangsa nu bakal datang.
