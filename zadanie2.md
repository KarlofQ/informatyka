
<h1>Sprawozdanie - Polecenia konsolowe - Karol Petryniak i Franciszek Nowak 2Ia gr.2</h1>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Polecenie 1 - Znajdź dokładne dopasowanie frazy w pliku tekstowym](#polecenie-1---znajdź-dokładne-dopasowanie-frazy-w-pliku-tekstowym)
- [Polecenie 2 - Znajdź frazy, ignorując wielkość liter](#polecenie-2---znajdź-frazy-ignorując-wielkość-liter)
- [Polecenie 3 - Znajdź całe słowa w pliku](#polecenie-3---znajdź-całe-słowa-w-pliku)
- [Polecenie 4 - Wyświetl wyniki z numerami linii i podkreślonymi dopasowaniami](#polecenie-4---wyświetl-wyniki-z-numerami-linii-i-podkreślonymi-dopasowaniami)
- [Polecenie 5 - Zlicz liczbę dopasowań frazy w pliku](#polecenie-5---zlicz-liczbę-dopasowań-frazy-w-pliku)
- [Polecenie 6 - Znajdź pliki lub katalogi zawierające określoną frazę w nazwie](#polecenie-6---znajdź-pliki-lub-katalogi-zawierające-określoną-frazę-w-nazwie)
- [Polecenie 7 - Znajdź pliki o określonym rozszerzeniu](#polecenie-7---znajdź-pliki-o-określonym-rozszerzeniu)
- [Polecenie 8 - Zlicz liczbę znalezionych plików](#polecenie-8---zlicz-liczbę-znalezionych-plików)
- [Polecenie 9 - Znajdź pliki utworzone w ciągu ostatniego tygodnia](#polecenie-9---znajdź-pliki-utworzone-w-ciągu-ostatniego-tygodnia)
- [Polecenie 10 - Znajdź pliki o rozmiarze większym niż 2 MB](#polecenie-10---znajdź-pliki-o-rozmiarze-większym-niż-2-mb)
- [Polecenie 11 - Znajdź słowa w plikach tekstowych](#polecenie-11---znajdź-słowa-w-plikach-tekstowych)

---

## Polecenie 1 - Znajdź dokładne dopasowanie frazy w pliku tekstowym

```bash
grep "fraza" plik.txt
```

## Polecenie 2 - Znajdź frazy, ignorując wielkość liter

```bash
grep -i "fraza" plik.txt
```

## Polecenie 3 - Znajdź całe słowa w pliku

```bash
grep -w "fraza" plik.txt
```

## Polecenie 4 - Wyświetl wyniki z numerami linii i podkreślonymi dopasowaniami

```bash
grep --color=always -n "fraza" plik.txt
```

## Polecenie 5 - Zlicz liczbę dopasowań frazy w pliku

```bash
grep -c "fraza" plik.txt
```

## Polecenie 6 - Znajdź pliki lub katalogi zawierające określoną frazę w nazwie

```bash
find /ścieżka -name "*fraza*"
```

## Polecenie 7 - Znajdź pliki o określonym rozszerzeniu

```bash
find /ścieżka -name "*.txt"
find /ścieżka -name "*.png"
```

## Polecenie 8 - Zlicz liczbę znalezionych plików

```bash
find /ścieżka -name "*.txt" | wc -l
```

## Polecenie 9 - Znajdź pliki utworzone w ciągu ostatniego tygodnia

```bash
find /ścieżka -type f -mtime -7
```

## Polecenie 10 - Znajdź pliki o rozmiarze większym niż 2 MB

```bash
find /ścieżka -type f -size +2M
```

## Polecenie 11 - Znajdź słowa w plikach tekstowych

```bash
find /ścieżka -name "*.txt" -exec grep -H "słowo" {} \;
```
