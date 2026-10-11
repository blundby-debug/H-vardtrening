# Oppsett — Håvards treningsapp

## Deploy på GitHub Pages

1. Gå til github.com → **New repository**
2. Navn: `havardTrening` (eller hva du vil), sett til **Public**
3. Huk av "Add a README file" → **Create repository**
4. Klikk **Add file → Upload files**
5. Dra inn **alle disse filene**: `index.html`, `manifest.json`, `ikon-180.png`, `ikon-192.png`, `ikon-512.png` → **Commit changes**
6. Gå til **Settings → Pages**
7. Under "Source": velg **Deploy from a branch**, branch = `main`, folder = `/ (root)` → **Save**
8. Vent 1–2 minutter. URL blir:
   `https://DITTBRUKERNAVN.github.io/havardTrening/`

## Installer på telefonen (Håvard)

**iPhone:** Åpne URL-en i **Safari** (ikke Chrome) → del-ikonet → **Legg til på Hjem-skjerm**

**Android:** Åpne i Chrome → tre prikker → **Legg til på startskjerm**

## VIKTIG for iOS

Hvis han sletter snarveien fra hjem-skjermen og legger den til på nytt, **får appen ny localStorage og all logg forsvinner**. Samme skjer ved bytte av telefon.

Løsning: bruk **Meny (⋯) → Eksporter backup** jevnlig. Kopier teksten og lagre den i Notater eller send den til seg selv. Gjenopprettes via **Importer backup**.

## Hvordan progresjonen fungerer

Under hver øvelse vises en linje som sier hva han skal gjøre, basert på forrige økt:

- **↑ Øk til X kg** — alle sett nådde toppen av rep-området sist
- **→ Hold X kg** — han er inne i rep-området, jag flere reps
- **↓ Hold X kg** — han falt under bunnen av området, bygg reps først

Reglene per øvelse:
- Benkpress, skulderpress, incline: +2,5 kg
- Knebøy, markløft, RDL, leg curl: +5 kg
- Leg press: +10 kg
- Isolasjon (curls, hev, flyes): +2 kg

## Hviletider (auto-start ved ✓)

| Type | Tid |
|---|---|
| Markløft | 4:00 |
| Knebøy | 3:30 |
| Benkpress / skulderpress / incline | 3:00 |
| Hantelpress / RDL | 2:30 |
| Split squat / leg press | 2:00 |
| Ro / pulldown / leg curl | 1:30 |
| Isolasjon | 1:00–1:15 |

Trykk ✓ på et sett → timeren starter automatisk med riktig tid. Vibrasjon + lyd når den er ferdig.
