# ProfiELEKTRO - Netlify Deploy

## 🚀 Jak nahrát na Netlify:

### Způsob 1: Drag & Drop (nejjednodušší)

1. Jděte na https://netlify.com
2. Přihlaste se (Gmail/GitHub)
3. Klikněte "Add new site" → "Deploy manually"
4. Přetáhněte CELOU tuto složku na stránku
5. Počkejte 30 sekund
6. HOTOVO! Dostanete odkaz typu:
   ```
   https://profi-elektro-xyz.netlify.app
   ```

### Způsob 2: Netlify CLI

```bash
npm install -g netlify-cli
netlify login
netlify deploy --prod
```

---

## 📱 Po nahrání:

1. Otevřete odkaz v prohlížeči
2. Klikněte na ⊕ v adresním řádku
3. "Nainstalovat ProfiELEKTRO"
4. Aplikace je na ploše!

---

## 🔧 Vlastní doména:

1. V Netlify: Site settings → Domain management
2. Přidejte svou doménu (např. nabidky-elektro.cz)
3. Nastavte DNS záznamy
4. HOTOVO!

---

## 📊 Co obsahuje tato složka:

- `index.html` - Hlavní aplikace
- `manifest.json` - PWA konfigurace
- `service-worker.js` - Offline podpora
- `icon.svg` - Ikona aplikace
- `netlify.toml` - Netlify nastavení
- `_redirects` - SPA routing

---

## ✅ Funkce po nahrání:

- ✅ HTTPS automaticky
- ✅ PWA instalace
- ✅ Offline režim
- ✅ Import ELFETEX ceníku
- ✅ PDF export
- ✅ Všechny funkce aplikace

---

**Prostě přetáhněte tuto složku na Netlify a je to!** 🎉
