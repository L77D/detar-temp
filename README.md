# DETAR — Demo-Karte (temporär)

Kopie der Engine aus `L77D/v2tracker` (`main`, Build 111, Stand 2026-10-15)
mit genau einer Karte: **`demo`** (Elektroniker*in für Betriebstechnik bei
„Musterbetrieb", neutrale Beispielfassung mit Platzhalter-Logo).

**Link:** https://l77d.github.io/detar-temp/?karte=demo (auch `?k=demo`)

- Erkennungsbild = Testdruck **P04** (04_2809_1, 63 × 88 mm) — dieselben
  Erkennungsdaten wie `karten/000/targets/p04.*` im Haupt-Repo. Zum Testen die
  gedruckte P04-Karte scannen.
- Public-Fassung: `?k=demoP` gibt es nicht (der Alias gilt nur hinter Ziffern);
  bei Bedarf ein zweites Design mit `"fassung": "public"` anlegen.
- QR-Code zum Link: `karten.html` im Browser öffnen.
- Alles Weitere (Aufbau, URL-Parameter, Konventionen) steht in
  `L77D/v2tracker` → `CLAUDE.md` und `docs/`. Dieses Repo ist nur die
  Auslieferung einer Demo; Engine-Änderungen gehören ins Haupt-Repo.
