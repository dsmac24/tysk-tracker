Website-mappe — "German market tracker"
=======================================
Denne mappe udgiver "German market tracker" — ÉN side med top-toggle mellem to faner:
  • Bonusser og tilbud  (opdateres dagligt)
  • Produkter            (slots-udbud; opdateres ugentligt)
(Sportsmarkedet er ikke med i den tyske tracker.)

UDGIVELSE — GitHub Pages (anbefalet, automatisk):
Mappen er et git-repo. Engangs-opsætning: dobbeltklik 'opsaet-github.command'
i mappen ovenover og følg trinene (se også Dokumentation/GITHUB-opsaetning.md).
Herefter committer og pusher Macens daglige job (_daglig_push.sh, kl. 07:00)
selv den nye index.html — GitHub Pages opdaterer siden ~1 minut senere.

ALTERNATIV — Netlify (manuel drag-and-drop):
1. Åbn https://app.netlify.com/drop
2. Træk HELE denne mappe (Netlify-site) ind i feltet — ikke kun filen.
3. Vent ~10 sekunder — siden er live på en netlify.app-adresse.

Opdatering: index.html skrives automatisk af german_market_tracker_generator.py
(kører efter bonus- og produkt-generatorerne og samler de nyeste udgaver).
index.html er selvstændig — alle billeder er indlejret som base64, så intet andet skal med.
