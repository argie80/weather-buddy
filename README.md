# ⛅ WeatherBuddy — Εφαρμογή Καιρού για iOS (PWA)

Μια ελαφριά, γρήγορη εφαρμογή καιρού σε καθαρή HTML/CSS/JS, σχεδιασμένη για να φιλοξενείται δωρεάν στο **GitHub Pages** και να αποθηκεύεται ως native-like εφαρμογή στην Οθόνη Αφετηρίας του **iPhone (iOS)**.

## ✨ Δυνατότητες
- **Δωρεάν δεδομένα καιρού (Open-Meteo)**: Λειτουργεί αμέσως χωρίς API key.
- **Αυτόματος εντοπισμός τοποθεσίας (GPS)**: Εντοπίζει πού βρίσκεστε με ένα πάτημα στο κουμπί `📍 GPS`.
- **Αναζήτηση πόλης**: Live αναζήτηση στα Ελληνικά ή Αγγλικά για οποιαδήποτε πόλη στον κόσμο, καθώς και γρήγορη επιλογή ελληνικών πόλεων.
- **Πλήρης πρόγνωση**: Τρέχουσα θερμοκρασία, αίσθηση, άνεμος (σε km/h & Μποφόρ), υγρασία, δείκτης UV, ωριαία πρόγνωση 24ώρου και πρόγνωση 7 ημερών.
- **iOS Web App (PWA)**: Υποστηρίζει πλήρη οθόνη (χωρίς τη γραμμή του Safari), εικονίδιο εφαρμογής (`icon-180.png`) και προσωρινή αποθήκευση (offline cache).

---

## 🚀 Πώς να το ανεβάσεις στο GitHub Pages

1. Δημιούργησε ένα νέο **Public** repository στο GitHub (π.χ. `weatherbuddy`).
2. Ανέβασε όλα τα αρχεία του φακέλου (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-180.png`, `icon-512.png`):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: WeatherBuddy iOS PWA"
   git branch -M main
   git remote add origin https://github.com/argie80/weather-buddy.git
   git push -u origin main
   ```
3. Στο GitHub, πήγαινε στο **Settings** → **Pages** (στην αριστερή στήλη): https://github.com/argie80/weather-buddy/settings/pages
4. Στο **Build and deployment** → **Source**, επίλεξε **Deploy from a branch**.
5. Επίλεξε το branch **`main`** και φάκελο **`/ (root)`** και πάτησε **Save**.
6. Μετά από ~1 λεπτό, η εφαρμογή σου θα είναι online στη διεύθυνση:
   **https://argie80.github.io/weather-buddy/**

---

## 📲 Πώς να το αποθηκεύσεις ως App στο iPhone (iOS)

1. Άνοιξε το link του GitHub Pages στο **Safari** από το iPhone σου.
2. Πάτησε το κουμπί **Κοινοποίηση (Share)** στο κάτω μέρος της οθόνης (το τετράγωνο με το βελάκι προς τα πάνω).
3. Κύλισε προς τα κάτω και επίλεξε **«Προσθήκη στην Οθόνη Αφετηρίας» (Add to Home Screen)**.
4. Πάτησε **Προσθήκη (Add)** πάνω δεξιά.

Η εφαρμογή **WeatherBuddy** θα εμφανιστεί στην αρχική οθόνη του iPhone σου με το δικό της εικονίδιο και θα ανοίγει σε πλήρη οθόνη σαν κανονικό iOS app!
