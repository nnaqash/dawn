# DFYNE – Frontend Developer Test (Shopify Variant Picker)

This project is a technical test where I recreated the **color variant picker** from DFYNE’s product page using the **Shopify Dawn theme**.

## 🛠 What I Did

- ✅ Forked and opened the **Shopify Dawn** theme using WSL and VS Code  
- ✅ Added a **custom color variant picker** with:
  - Variant images  
  - Color names (labels)  
  
- ✅ Used **Liquid**, **CSS**, and **JavaScript** inside the theme structure
- ✅ Styled the variant picker to match DFYNE’s UI (horizontal scroll, hover/focus effects)
- ✅ Enabled **variant switching** (simulated using `data-variant-id`)
- ✅ Built a local **`test.html`** file for browser testing without a dev store

## 📁 Main Files Modified

| File | Purpose |
|------|---------|
| `snippets/variant-picker.liquid` | Main variant picker markup using Liquid |
| `assets/variant-picker.css` | Custom styles for the swatches |
| `assets/global.js` | JavaScript for handling click logic & variant selection |
| `test.html` | A local file used to preview functionality without needing Shopify backend |

## 🎨 Features


- Click on a swatch updates the selected variant ID (logged in console)

## 💡 How to Test Locally

1. Clone the repo
2. Open `test.html` in a browser
3. Click on any color swatch to see the interaction
4. Check the browser console for the selected variant ID



## 🚀 Technologies Used

- Liquid (Shopify templating)
- HTML/CSS/JS
- Shopify Dawn theme
- VS Code with WSL



---

