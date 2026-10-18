# MedSpecialty Navigator 🩺
### Επιστημονικός Προσομοιωτής Επιλογής Ιατρικής Ειδικότητας
*Βασισμένο σε 7 Διεθνείς Μελέτες σε Ιατρικά Περιοδικά (AHP, Holland RIASEC, Controllable Lifestyle, Big Five Personality, Scoping & Systematic Reviews)*

---

## 📌 Περιγραφή Έργου

Το **MedSpecialty Navigator** είναι μια σύγχρονη, προσβάσιμη από όλους διαδικτυακή εφαρμογή (Web App), σχεδιασμένη ειδικά για φοιτητές ιατρικής και νέους ιατρούς που βρίσκονται στη διαδικασία επιλογής ειδικότητας.

Ο χρήστης βαθμολογεί **10 αντικειμενικές παραμέτρους (κλίμακα 1-10)** και το σύστημα παράγει:
1. **Top 5 Ιατρικές Ειδικότητες** με ποσοστό συμβατότητας (%), ταυτότητα κατηγορίας και Holland RIASEC code.
2. **Αναλυτική Επιστημονική Αιτιολόγηση** για κάθε ειδικότητα, συνδέοντας άμεσα τις απαντήσεις του φοιτητή με τα δημοσιευμένα πορίσματα των 7 επιστημονικών μελετών.
3. **Βασικά Πλεονεκτήματα & Σημεία Πίεσης (Pros & Cons)** της καθημερινής κλινικής πραγματικότητας.
4. **Διαδραστικό 2D Χάρτη Σταδιοδρομίας (Holland RIASEC 2D Map)** κατά Petrides & McManus (2004), όπου ο φοιτητής βλέπει τη θέση του σε πραγματικό χρόνο ανάμεσα στις 30 ειδικότητες.
5. **Πλήρη Κατάταξη Όλων των 30 Ιατρικών Ειδικοτήτων** με φίλτρα ανά κλινικό τομέα και αναζήτηση.
6. **Εκτύπωση & Εξαγωγή Αναφοράς (PDF)**.

---

## 🔬 Επιστημονική Τεκμηρίωση (Οι 7 Μελέτες)

Ο προσομοιωτής δεν βασίζεται σε αυθαίρετα βάρη, αλλά συνθέτει τα πραγματικά ερευνητικά δεδομένα των 7 άρθρων:

1. **Chang et al. (2006)** - *Journal of the Formosan Medical Association*  
   *«Factors Influencing Medical Students’ Choice of Specialty»*  
   - **Συνεισφορά:** Παρέχει τις ακριβείς μαθηματικές βαρύτητες μέσω **Analytic Hierarchy Process (AHP)** (14 κριτήρια σε 2 επίπεδα). Η «Προσωπική διανοητική ικανοποίηση/πρόκληση» έχει το υψηλότερο βάρος (19.7%), ακολουθούμενη από τις ευκαιρίες καριέρας (10.7%) και το lifestyle (9.4%).
2. **Petrides & McManus (2004)** - *BMC Medical Education*  
   *«Mapping medical careers: Questionnaire assessment of career preferences»*  
   - **Συνεισφορά:** Ομολογία του μοντέλου **Holland RIASEC** στην ιατρική και εξαγωγή των 2 ορθογώνιων αξόνων: **«Things vs People»** (Χειρουργική vs Ψυχιατρική/GP) και **«Data vs Ideas»** (Βιοπαθολογία vs Παθολογία).
3. **Resneck (2006)** - *Virtual Mentor (AMA Journal of Ethics)*  
   *«The influence of controllable lifestyle on medical student specialty choice»*  
   - **Συνεισφορά:** Εισαγωγή της κατηγορίας **Controllable Lifestyle** και της τάσης προς τις ειδικότητες **ROAD** (Δερματολογία, Ακτινολογία, Οφθαλμολογία, Αναισθησιολογία).
4. **Kiolbassa et al. (2011)** - *BMC Family Practice*  
   *«Becoming a general practitioner - Which factors have most impact on career choice»*  
   - **Συνεισφορά:** Παραγοντική ανάλυση 7 παραγόντων σε 1.299 φοιτητές. Ανέδειξε ότι η **Προσήλωση στον Ασθενή (Patient Orientation)** είναι ο νούμερο 1 στατιστικός προγνωστικός παράγοντας για τη Γενική Ιατρική.
5. **Peroš et al. (2025)** - *Croatian Medical Journal*  
   *«Personality traits and medical specialty preference: a scoping review»*  
   - **Συνεισφορά:** Συστηματική χαρτογράφηση 61 μελετών για χαρακτηριστικά προσωπικότητας (ανοχή στην αβεβαιότητα, αντοχή στο στρες, παρορμητικότητα/αποφασιστικότητα).
6. **Sarikhani et al. (2021)** - *BMC Medical Education*  
   *«A thematic network for factors affecting the choice of specialty education»*  
   - **Συνεισφορά:** Θεματικό δίκτυο 17 υπο-θεμάτων και 5 αξόνων (Life fulfillment, Career aspects, Personal determinants, Educational factors, Interpersonal effects).
7. **Herath et al. (2024)** - *Journal of Information Technology Education: Research*  
   *«Computer-Assisted Career Guidance Tools for Students’ Career Path Planning»*  
   - **Συνεισφορά:** Αρχιτεκτονική σύγχρονων εργαλείων CACG (Computer-Assisted Career Guidance) με πολυκριτηριακή στάθμιση, διανυσματικό ταίριασμα και επεξηγησιμότητα.

---

## 🧮 Μαθηματικός Αλγόριθμος

Για κάθε ειδικότητα $S$ και διάνυσμα απαντήσεων του χρήστη $U \in [1, 10]^{10}$, υπολογίζεται η σταθμισμένη κανονικοποιημένη Ευκλείδεια απόσταση (AHP-Weighted Normalized Euclidean Distance):

$$d(U, P_S) = \sqrt{ \sum_{i=1}^{10} w_i \left( \frac{|u_i - p_{S,i}|}{9} \right)^2 }$$

Όπου:
- $w_i$: Το βάρος του κριτηρίου $i$ προερχόμενο από τη μήτρα AHP των Chang et al. (2006).
- $u_i$: Η τιμή που επέλεξε ο φοιτητής (1 έως 10).
- $p_{S,i}$: Η πρότυπη τιμή της ειδικότητας $S$ στη βιβλιογραφία.

Το ποσοστό συμβατότητας υπολογίζεται μέσω της συνάρτησης συγγένειας (affinity scoring):

$$\text{Match \%} = \min\left(99.4\%, \; \max\left(18.0\%, \; 100 \cdot e^{-1.8 \cdot d(U, P_S)^{1.4}}\right)\right)$$

---

## 🚀 Ανέβασμα στο GitHub & Δημοσίευση στο GitHub Pages

Η εφαρμογή αποτελείται από καθαρό, αυτόνομο κώδικα (Static Web: HTML5, CSS3, JavaScript) χωρίς ανάγκη εξωτερικού server ή βάσης δεδομένων. Είναι 100% συμβατή με το **GitHub Pages**.

### Βήματα για δημοσίευση στο GitHub (σε 2 λεπτά):

1. **Δημιουργία νέου αποθετηρίου (Repository) στο GitHub:**
   - Συνδεθείτε στο [GitHub](https://github.com).
   - Πατήστε **New Repository** (π.χ. με όνομα `med-specialty-navigator`).
   - Επιλέξτε **Public** και μην προσθέσετε README (υπάρχει ήδη).

2. **Ανέβασμα των αρχείων μέσω τερματικού (Terminal):**
   Ανοίξτε το τερματικό μέσα στον φάκελο του project και εκτελέστε:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: MedSpecialty Navigator complete website"
   git branch -M main
   git remote add origin https://github.com/<ΤΟ_USERNAME_ΣΑΣ>/med-specialty-navigator.git
   git push -u origin main
   ```

3. **Ενεργοποίηση του GitHub Pages:**
   - Στη σελίδα του αποθετηρίου σας στο GitHub, μεταβείτε στο **Settings** (Ρυθμίσεις) $\rightarrow$ **Pages** (στην αριστερή στήλη).
   - Στο πεδίο **Build and deployment**:
     - **Source:** `Deploy from a branch`
     - **Branch:** `main` / `root`
     - Πατήστε **Save**.
   - Σε 30-60 δευτερόλεπτα η ιστοσελίδα σας θα είναι **ζωντανή και προσβάσιμη σε όλο τον κόσμο** στη διεύθυνση:
     `https://<ΤΟ_USERNAME_ΣΑΣ>.github.io/med-specialty-navigator/`

---

## 💻 Τοπική Εκτέλεση στον Υπολογιστή

Μπορείτε να ανοίξετε άμεσα το αρχείο `index.html` με διπλό κλικ σε οποιονδήποτε περιηγητή (Chrome, Safari, Firefox, Edge).

Εναλλακτικά, μέσω απλού τοπικού server:
```bash
# Python 3
python3 -m http.server 8000
```
Και επισκεφθείτε στο browser: `http://localhost:8000`

---

## 📁 Δομή Αρχείων

```
├── index.html          # Η κύρια ιστοσελίδα (HTML5)
├── README.md           # Οδηγός & επιστημονική τεκμηρίωση
├── css/
│   └── style.css       # Σύγχρονος responsive σχεδιασμός
├── js/
│   ├── data.js         # Βάση δεδομένων: 30 ειδικότητες, κριτήρια AHP, presets
│   ├── engine.js       # Μαθηματική μηχανή υπολογισμού AHP & RIASEC χάρτη
│   └── app.js          # Controller διεπαφής, φίλτρα, εκτύπωση, Canvas χάρτης
└── Άρθρα/              # Τα 7 αρχικά επιστημονικά PDFs
```

---

## 👨‍⚕️ Συντελεστές & Άδεια Χρήσης

Αναπτύχθηκε για φοιτητές ιατρικής και ιατρικούς συμβούλους σταδιοδρομίας.  
Διανέμεται ελεύθερα υπό την άδεια [MIT License](LICENSE).
