# 📝 Engelsktentamen – Karakterkalkulator

Et interaktivt verktøy for å effektivisere retting av engelsktentamen på ungdomstrinnet basert på vekting angitt av ENTER.

## Hva gjør den?

Kalkulatoren hjelper faglærere med å beregne samlet karakter basert på vurderingsskjemaet for tentamen i engelsk. I stedet for å regne manuelt, markerer du hvor eleven ligger på hvert kriterium – og kalkulatoren regner ut samlet karakter automatisk.

### Vektingen er som følger:

| Del | Innhold | Vekting |
|-----|---------|---------|
| Del 1 og 2 (lytting og lesing) | Karakter satt fra eget ark | 1/3 |
| Del 3, 4 og 5 – innholdsvurdering | Del 3: 1/4 · Del 4: 1/4 · Del 5: 1/2 | 1/3 |
| Del 3, 4 og 5 – helhetsvurdering | Samlet skjønn | 1/3 |

## Hvordan bruke den

1. Åpne `kalkulator.html` i en nettleser (ingen installasjon nødvendig)
2. Velg karakter for **del 1 og 2** ved å klikke på riktig karakterknapp (inkl. plusser og minuser)
3. Dra **sliderne** for hvert kriterium i del 3, 4 og 5 til der eleven ligger:
   - 🔴 Rød sone = lav måloppnåelse (karakter 1–2)
   - 🟡 Gul sone = middels måloppnåelse (karakter 3–4)
   - 🟢 Grønn sone = høy måloppnåelse (karakter 5–6)
   - Innenfor hver sone graderes det videre med −, hel og + karakter
4. Sett **helhetsvurderingen** for del 3–5
5. Kalkulatoren viser samlet gradert karakter (f.eks. **3+**) og råsnitt i parentes

## Filer

```
├── kalkulator.html   # Selve kalkulatoren – åpnes direkte i nettleser
└── README.md         # Denne filen
```

## Tilpasning

Vektingen og kriteriene er satt opp for en bestemt tentamenmal, men koden er enkel å justere. Karaktertrinn, sonenavn og vekting ligger øverst i JavaScript-delen av `kalkulator.html`.

## Lisens

Fri til bruk, deling og tilpasning. Laget for lærere, av en lærer. 🎓
