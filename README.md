# 🇸🇦 Saudi Riyal Symbol

[![License: GPL v2](https://img.shields.io/badge/license-GPL--2.0-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![Official Page](https://img.shields.io/badge/Official%20Page-arib.sa-blue)](https://plugins.arib.sa/saudi-riyal-symbol/)

<img src="assets/images/Saudi_Riyal_Symbol-2.svg" alt="Saudi Riyal Symbol" width="150" />

A WordPress + WooCommerce plugin that replaces the SAR (Saudi Riyal) currency symbol with the official glyph from the **Saudi_Riyal** font.  
💡 Supports both RTL (Arabic) and LTR (English) layouts.

---

## 🌟 Features

- Automatic RTL / LTR layout support
- Uses actual glyph (U+E900) from the embedded font
- Fonts included — no external requests
- GPL‑2.0 License — open-source
- Works instantly after activation

---

## 📦 Installation

1. Download the latest version from the official GitHub repository:  
   👉 [https://github.com/AribSudia/Saudi-Riyal-Symbol-Woocommerce-WP-Plugin](https://github.com/AribSudia/Saudi-Riyal-Symbol-Woocommerce-WP-Plugin)
   
2. Or clone using Git:
   ```bash
   git clone https://github.com/AribSudia/Saudi-Riyal-Symbol-Woocommerce-WP-Plugin.git
   ```

3. Upload the plugin folder to your `/wp-content/plugins/` directory.

4. Activate the plugin from the WordPress dashboard.

---

## 🧪 Free License Activation

- To activate the plugin, you must obtain a free license key.
- Simply fill out the form at: [https://plugins.arib.sa/saudi-riyal-symbol/](https://plugins.arib.sa/saudi-riyal-symbol/)
- After submitting your email, you will receive the license key by email.
- Enter the license key inside the plugin's license page to enable full features.
- Without license activation, the plugin features will not work.
- A 90-day free trial period starts after license activation.

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
  <bdi><span class="srs-glyph">&#xE900;</span> ٢٩٩٫٠٠</bdi>
</span>
```

---

## 🎨 Customization

To change the symbol's color or size:
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
├── saudi-riyal-symbol.php
```

---

## 📃 License

This plugin is licensed under the [GPL v2 or later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

---

## 🧐 Developed by

**[Arib Information Technology](https://arib.sa)**  
Official Plugin Page: [https://plugins.arib.sa/saudi-riyal-symbol/](https://plugins.arib.sa/saudi-riyal-symbol/)
