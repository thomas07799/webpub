# 🍔 rsBurger Website

**Professionelles Burger-Catering Berlin & Brandenburg**

## Struktur

```
rsburger/
├── index.html        → rsburger.de/
├── oszimt/
│   └── index.html    → rsburger.de/oszimt/
└── README.md
```

## GitHub Pages aktivieren

1. Repo auf github.com anlegen (Name: `rsburger`)
2. Dateien pushen
3. **Settings → Pages → Branch: main → Save**
4. Live in ~2 Minuten

## Custom Domain (IONOS → rsburger.de)

DNS A-Records bei IONOS setzen:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
CNAME: `www` → `dein-github-username.github.io`

Dann GitHub Pages → Custom domain: `rsburger.de` eintragen.

## Lokal testen

```bash
cd rsburger
python3 -m http.server 8080
# http://localhost:8080        → Hauptseite
# http://localhost:8080/oszimt → OSZ-Seite
```

## Kontakt
📧 sekretariat.rsburger@gmail.com
