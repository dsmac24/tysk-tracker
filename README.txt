Deploy til Netlify (drag-and-drop)
=================================
Denne mappe udgiver "German market tracker" — ÉN side med top-toggle mellem to faner:
  • Bonusser og tilbud  (opdateres dagligt)
  • Produkter            (slots-udbud; opdateres ugentligt)

1. Åbn https://app.netlify.com/drop
2. Træk HELE denne mappe (Netlify-site) ind i feltet — ikke kun filen.
3. Vent ~10 sekunder — siden er live på en netlify.app-adresse.

Opdatering: index.html skrives automatisk af german_market_tracker_generator.py
(kører efter bonus- og produkt-generatorerne og samler de nyeste udgaver).
Træk mappen ind igen efter en ny kørsel — eller forbind et Git-repo for automatisk deploy.
index.html er selvstændig — alle billeder er indlejret som base64, så intet andet skal med.
