# 🎯 Rovnice Trenažér

Interaktivní webová aplikace pro procvičování matematických rovnic a mocnin, optimalizovaná pro děti a studenty.

## ✨ Funkce

- **4 úrovně obtížnosti** s různými typy příkladů
- **Postupné řešení** krok za krokem
- **Moderní UI** s animacemi a gradienty
- **Touch ovládání** pro mobily
- **Progressive Web App** - funguje offline
- **Responsive design** pro všechna zařízení

## 🎮 Úrovně obtížnosti

### 🟢 Snadné
- Základní sčítání a odčítání
- Rovnice typu: `x + 5 = 12`, `x - 3 = 8`

### 🟡 Složitější  
- Všechny základní operace (+, -, ×, ÷)
- Rovnice typu: `3x = 15`, `x/4 = 3`

### 🔴 Složité
- Rovnice s více neznámými
- Rovnice typu: `2x + 3x = 25`, `5x - 2x = 18`

### ⚡ Mocniny
- Složité příklady s odmocninami a mocninami
- Typy příkladů:
  - `√2500 - 2 × √625 = ?`
  - `(−1,3)² - 2 × √0,49 = ?`
  - `(√144 × 7 + 4²)² = ?`
  - `√64 / (−3)² = ?`
  - `√((20 - 2²) / 4) = ?`
  - `3 × √(−5)² + √7² = ?`
  - `√5 × √(3/5) × √(12/25) = ?`
  - `3 × √x - 4 = 5` (rovnice)

## 🚀 Jak spustit

### Rychlé spuštění
1. Otevřete soubor `index.html` v prohlížeči
2. Aplikace se spustí okamžitě

### Doporučené spuštění (s HTTP serverem)
```bash
# Přejděte do složky s aplikací
cd /cesta/k/aplikaci

# Spusťte lokální server
python3 -m http.server 8000

# Otevřete v prohlížeči
# http://localhost:8000
```

### Alternativní způsoby
```bash
# Node.js
npx serve .

# PHP
php -S localhost:8000
```

## 📱 Použití

1. **Vyberte úroveň** - klikněte na tlačítko obtížnosti (vpravo nahoře)
2. **Zobrazte postup** - klikněte "ZOBRAZIT POSTUP"
3. **Postupujte krok za krokem** - klikněte "DALŠÍ KROK"
4. **Další příklad** - klikněte "DALŠÍ PŘÍKLAD" nebo swipe nahoru

## 🛠️ Technologie

- **HTML5** - struktura
- **CSS3** - styling s Tailwind CSS
- **JavaScript** - logika aplikace
- **React** - komponenty (CDN)
- **Babel** - transpilace JSX
- **Service Worker** - offline funkcionalita

## 📁 Struktura souborů

```
/
├── index.html          # Hlavní soubor aplikace
├── manifest.json       # PWA manifest
├── sw.js              # Service Worker
└── README.md          # Tento soubor
```

## 🎯 Cílové publikum

- **Žáci 6.-9. třídy** - základní rovnice
- **Středoškoláci** - složitější rovnice a mocniny
- **Učitelé** - pro výuku matematiky
- **Rodiče** - pro domácí procvičování

## 🔧 Přizpůsobení

Aplikace je navržena tak, aby byla snadno rozšiřitelná:

- **Nové typy příkladů** - přidejte do funkce `generateEq()`
- **Nové úrovně** - rozšiřte pole obtížností
- **Styling** - upravte CSS třídy nebo Tailwind konfiguraci

## 📄 Licence

Tento projekt je open source a volně použitelný pro vzdělávací účely.

## 🤝 Přispívání

Vítáme jakékoliv návrhy na vylepšení nebo opravy chyb!

---

**Vytvořeno s ❤️ pro lepší výuku matematiky**
