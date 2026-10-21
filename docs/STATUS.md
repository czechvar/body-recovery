# Stav a úkoly

Stav k 21. 10. 2026.

## Hotovo

- **Tělo zpět** (`czechvar/body-recovery`): appka podle Šlacha zpět pro Jakuba. 8týdenní plán na celé tělo doma
  s jednoručkami, 10–15 minut denně, tři sestavy A/B/C na střídání, zápis vah, svalovka, řada dní v řadě, indigo vzhled.
- Běží bez Firebase (data jen v prohlížeči telefonu).

## Zbývá

1. **GitHub Pages**: Settings → Pages → Source: **GitHub Actions** (pokud se nezapnulo samo prvním nasazením).
2. Volitelně **Firebase** pro sdílení s parťákem: vlastní projekt `telo-zpet` podle [FIREBASE.md](FIREBASE.md),
   konfiguraci do `js/firebase-config.js` nebo do secretu `FIREBASE_CONFIG`. Pak Nastavení → Nahrát plán do databáze.
3. Volitelně **upozornění**: vlastní VAPID pár (`tools/vapid.html`), veřejný klíč do `js/push.js`,
   secrets `VAPID_PRIVATE_KEY` a `FIREBASE_SERVICE_ACCOUNT` podle [NOTIFICATIONS.md](NOTIFICATIONS.md). Funguje jen s Firebase.
4. Na telefonu přidat appku na plochu (Android Chrome ⋮ → Instalovat aplikaci; iPhone Safari → Sdílet → Přidat na plochu).
