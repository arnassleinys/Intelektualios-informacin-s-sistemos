
# Duomenų rinkinio aprašymas

Magistrinio darbo tikslas – sukurti dirbtiniu intelektu
paremtą automatinio žodinių atsakymų vertinimo sistemą.

## Įvesties duomenys (X)

- Žodinis atsakymas (garso įrašas).
- Klausimas.
- Etaloninis atsakymas.

## Tikslinė reikšmė (y)

Žmogaus vertintojo suteiktas žodinio atsakymo įvertinimas.

## Duomenų (X, y) pavyzdžiai

| Garso failas | Klausimas | Etaloninis atsakymas | Žodinio atsakymo transkripcija | Įvertinimas (y) |
| --- | --- | --- | --- | --- |
| answer_01.wav | Kas yra RAM? | Laikinoji atmintis, kurios turinys prarandamas išjungus maitinimą. | RAM laikinai saugo duomenis. | 10 |
| answer_02.wav | Kas yra RAM? | Laikinoji atmintis, kurios turinys prarandamas išjungus maitinimą. | RAM saugo informaciją. | 5 |
| answer_03.wav | Kas yra RAM? | Laikinoji atmintis, kurios turinys prarandamas išjungus maitinimą. | RAM yra procesorius. | 1 |

Pateikti pavyzdžiai yra iliustraciniai ir demonstruoja
preliminarią įvesties duomenų bei tikslinių reikšmių struktūrą.

## Prognozuojamas rezultatas (y)

Dirbtinio intelekto sistema, atlikusi žodinio atsakymo
analizę, prognozuoja atsakymo įvertinimą (y).

Sistemos sugeneruotas įvertinimas gali būti palyginamas
su žmogaus vertintojo suteiktu įvertinimu (y), siekiant
nustatyti sistemos tikslumą.
test