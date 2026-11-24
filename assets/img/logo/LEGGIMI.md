# Logo web

Originale (non in git): `02_RISORSE/originali/logo-vaquero-mountain-ranch-v1.jpg` (fondo uniforme `#E6DFCD`).
Ritaglio usato: x 100–1500, y 200–1230. File qui:
- `logo-vaquero.webp` + `logo-vaquero.jpg` (1120×824): hero e pagine di servizio
- `logo-vaquero-header.jpg` (152×112): header e footer su piastrina `--logo-piastrina`

## Quando arriva il PNG trasparente (Jessy)
1. Creare `logo-vaquero.png` (e `.webp` con trasparenza) e `logo-vaquero-header.png`, stessi ritagli e misure.
2. Cerca-e-sostituisci in tutte le pagine di `03_CODICE/`: `logo-vaquero.jpg` → `logo-vaquero.png`, `logo-vaquero-header.jpg` → `logo-vaquero-header.png` (e `.webp` nei `<source>` se serve).
3. In `assets/css/stile.css`, in `:root`: `--logo-piastrina: transparent;`
Nient'altro da cambiare. Dettagli: `01_PROGETTO/design-sistema.md` §5.
