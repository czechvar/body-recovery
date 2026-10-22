# Stav a úkoly

Stav k 21. 10. 2026.

## Hotovo

- **Tělo zpět** (`czechvar/body-recovery`): appka podle Šlacha zpět pro Jakuba. 8týdenní plán na celé tělo doma
  s jednoručkami, 10–15 minut denně, tři sestavy A/B/C na střídání, zápis vah, svalovka, řada dní v řadě, indigo vzhled.
- Firebase: vlastní projekt `telo-zpet` (europe-west1), konfigurace v `js/firebase-config.js`.

## Zbývá

1. ~~GitHub Pages~~ hotovo, běží na https://czechvar.github.io/body-recovery/
2. **Firebase**: zkontrolovat, že pravidla z `database.rules.json` jsou publikovaná, a v appce Nastavení → Nahrát plán do databáze.
3. **Upozornění**: veřejný VAPID klíč je v `js/push.js`. Zbývají secrets `VAPID_PRIVATE_KEY` a
   `FIREBASE_SERVICE_ACCOUNT` podle [NOTIFICATIONS.md](NOTIFICATIONS.md), pak Actions → Upozornění → Run workflow.
4. Na telefonu přidat appku na plochu (Android Chrome ⋮ → Instalovat aplikaci; iPhone Safari → Sdílet → Přidat na plochu).
