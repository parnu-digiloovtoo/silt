# Testimine

Kasutage kontrollitavat näidisaega, et testida tunni piire päris tunnivahetust ootamata.

| Katse | Oodatav tulemus |
|---|---|
| Enne päeva esimest tundi | Tunnivälise aja teade ja päevaplaan |
| Tunni algushetk | Algava tunni õiged andmed |
| Tunni keskpaik | Sama tunni õiged andmed |
| Tunni lõpuhetk | Lõppenud tund pole enam käimasolev |
| Vahetund | Tunnivälise aja teade |
| Pärast viimast tundi | Tunnivälise aja teade |
| Tundideta päev | Arusaadav teade |
| Puuduv või vigane andmestik | Veateade, mitte eksitav tunniinfo |
| Pikad nimed | Tekst püsib loetav ega kattu |
| Taaskäivitamine | Prototüüp avaneb juhendi järgi |

Tunni ajavahemikku tõlgendame kujul algus kaasa arvatud, lõpp välja arvatud. Näiteks 10.00–10.45 tund enam kell 10.45 ei kesta.

Kasutajakatse ülesanne: „Leia praegune õpperühm ja õpetaja.” Märkige kulunud aeg ja abi vajadus. Kontrollige ka loetavust kokkulepitud ekraanil ja kauguselt.

Tulemused salvestage `tests/tulemused.md` faili. Probleemist looge veateade, paranduse järel korrake katset.
