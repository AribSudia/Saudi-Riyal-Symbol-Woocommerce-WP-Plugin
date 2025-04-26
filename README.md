# 🇸🇦 Saudi Riyal Symbol | رمز الريال السعودي

[![License: GPL v2](https://img.shields.io/badge/license-GPL--2.0-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![Plugin Page](https://img.shields.io/badge/Official%20Page-arib.sa-blue)](https://arib.sa/plugins/saudi-riyal-symbol)

<img src="assets/images/Saudi_Riyal_Symbol-2.svg" alt="Saudi Riyal Symbol" width="150" />

A WordPress + WooCommerce plugin that replaces the SAR (Saudi Riyal) currency symbol with the official glyph from the **Saudi_Riyal** font.  
💡 Supports both RTL (Arabic) and LTR (English) layouts.

---

## 🌟 Features

- Automatic RTL / LTR layout support  
- Uses actual glyph (U+E900) from embedded font  
- Fonts included — no external requests  
- GPL‑2.0 License — open source  
- Works instantly after activation

---

## 📦 Installation

1. Download the latest version:  
   👉 [https://arib.sa/plugins/saudi-riyal-symbol  ](https://plugins.arib.sa/saudiriyalsymbol)
   or clone from GitHub:
   ```bash
   git clone https://github.com/AribSudia/Saudi-Riyal-Symbol-Woocommerce-WP-Plugin.git
   ```

2. Upload to your `/wp-content/plugins/` directory.

3. Activate the plugin from the WordPress dashboard.

4. **Activate your free license:**
   - Get your free license code from: [https://plugins.arib.sa/saudiriyalsymbol](https://plugins.arib.sa/saudiriyalsymbol)
   - Enter the license key on the plugin's license page in your WordPress dashboard.
   - Enjoy full features for free!

5. Clear your cache and check any WooCommerce product or price display.

---

## 🧪 Free License Activation

- After installing and activating the plugin, you must enter a license code.
- The license is provided **free of charge** from: [https://plugins.arib.sa/saudiriyalsymbol](https://plugins.arib.sa/saudiriyalsymbol).
- Without activating the license, the plugin features will not work.
- Upon activation, a 90-day free trial starts. You will be reminded to upgrade before the period ends.

---

## 🧪 Example Output

### English (LTR):
```html
<span class="woocommerce-Price-amount amount">
  <bdi>299.00 <span class="srs-glyph">&#xE900;</span></bdi>
</span>
```

### Arabic (RTL):
```html
<span class="woocommerce-Price-amount amount">
  <bdi><span class="srs-glyph">&#xE900;</span> ٢٩٩ٮ٠٠</bdi>
</span>
```

---

## 🎨 Customization

To change the color or size of the symbol:
```css
.srs-glyph {
  color: #000000;
  font-size: 1.2em;
}
```

---

## 👢 Folder Structure
```
saudi-riyal-symbol/
├── assets/
│   ├── css/
│   │   └── saudi-riyal.css
│   └── fonts/
│       ├── saudi_riyal.ttf
│       ├── saudi_riyal.woff
│       └── saudi_riyal.woff2
└── saudi-riyal-symbol.php
```

---

## 📃 License

This plugin is licensed under the [GPL v2 or later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

---

## 🧐 Developed by

**[Arib Information Technology](https://arib.sa)**  
Official Plugin Page: [https://arib.sa/plugins/saudi-riyal-symbol](https://arib.sa/plugins/saudi-riyal-symbol)
