# Google Colab dokumentų analizė

## 1. Demo_video_multimodal_extraction

### Paskirtis

Programos paskirtis – iš vaizdo įrašų išgauti
skirtingų tipų duomenis: garsą, tekstą ir vaizdus.

### Veikimo principas

1. Iš „Kaggle“ atsisiunčiamas duomenų rinkinys.
2. Naudojant „MoviePy“ biblioteką, iš vaizdo įrašų
   išgaunami garso įrašai (MP3).
3. Naudojant „Whisper Medium“ dirbtinio intelekto
   modelį, garso įrašai paverčiami tekstu (TXT).
4. Iš kiekvieno vaizdo įrašo išgaunamas vidurinis
   kadras (JPG).
5. Tekstai ir vaizdai archyvuojami bei išsaugomi
   „Google Drive“ saugykloje.

### Įvestis ir rezultatas

- Įvestis – vaizdo įrašai (MP4).
- Rezultatas – garso įrašai, tekstinės transkripcijos
  ir vaizdo kadrai.

### Sąsaja su magistriniu darbu

Magistriniame darbe taip pat numatoma naudoti
„Whisper“ modelį, kuris žodinį atsakymą paverstų
tekstine forma tolesnei atsakymo analizei ir vertinimui.

---

## 2. Demo_image_description_generation

### Paskirtis

Programos paskirtis – naudojant dirbtinį intelektą
automatiškai generuoti tekstinius vaizdų aprašymus.

### Veikimo principas

1. Prisijungiama prie „Google Drive“ ir
   sukonfigūruojamas API raktas.
2. Išarchyvuojami pirmojoje programoje išgauti
   vaizdo kadrai.
3. Vaizdas ir tekstinė instrukcija perduodami
   multimodaliniam „Gemma 3 27B IT“ modeliui.
4. Dirbtinio intelekto modelis sugeneruoja
   tekstinį vaizdo aprašymą.
5. Sugeneruoti aprašymai išsaugomi TXT failuose,
   archyvuojami ir įkeliami į „Google Drive“.

### Įvestis ir rezultatas

- Įvestis – vaizdas ir tekstinė instrukcija.
- Rezultatas – dirbtinio intelekto sugeneruotas
  tekstinis vaizdo aprašymas.

### Sąsaja su magistriniu darbu

Panašus duomenų apdorojimo principas gali būti
taikomas automatiniam žodinių atsakymų vertinimui.
Dirbtinio intelekto modeliams perduodami atsakymo
duomenys, kurie analizuojami pagal nustatytus
vertinimo kriterijus.

---

## Apibendrinimas

Abu dokumentai demonstruoja nuoseklų duomenų
apdorojimo procesą nuo pradinių duomenų įvesties
iki galutinio rezultato.

Abiejose programose naudojami iš anksto apmokyti
dirbtinio intelekto modeliai, kurie papildomai
neapmokomi.

Pateikti pavyzdžiai padeda formuoti magistrinio
darbo sistemos veikimo architektūrą ir duomenų
apdorojimo proceso modelį.
