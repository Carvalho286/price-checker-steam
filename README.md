# 🔍 Steam Market Price Checker
<!-- Title with a small icon for style -->

A simple web tool to check the price of items on the Steam Community Market.  
Originally built for personal use, but feel free to try it out or improve it.
<!-- Short description and purpose -->

---

## 🚀 Getting Started
<!-- Quick instructions for how to run it -->

You can run this project locally using the **Live Server** extension in **Visual Studio Code**.

---

## 🧾 How to Use
<!-- Simple step-by-step explanation -->

1. **Game ID**  
   Enter the numeric App ID of the game.  
   Example: `730` for *Counter-Strike 2*

2. **Item Name**  
   Enter the item's exact market name as it appears in the Steam Market URL, with proper URL encoding.  
   Example:  
   To check the **Fever Case**, enter:  
```
Fever%20Case
```
(Spaces become `%20`, etc.)

---

## ⚠️ Notes
<!-- Important things to know / limitations -->

- This tool uses the [Steam Community Market API](https://steamcommunity.com/market/).
- It currently uses a basic input format and requires URL-encoded item names.
- The UI and usability are minimal by design — just a quick tool for checking prices.
- **Future improvements** may include:
- Friendlier input handling
- Search suggestions
- Error feedback
- Better styling and responsiveness

---

## 🛠️ Tech Used
<!-- What technologies were used -->

- HTML, CSS, JavaScript
- Steam Market API
- Runs entirely client-side (no server needed)
