# Πολιτική απορρήτου – ATEKE Photos

Αυτός ο φάκελος περιέχει τη σελίδα πολιτικής απορρήτου για την εφαρμογή **ATEKE Photos**, έτοιμη για δημοσίευση στο GitHub Pages.

## Πώς να τη βάλετε στο GitHub και να πάρετε URL

### Επιλογή Α: Νέο repository μόνο για την πολιτική

1. Δημιουργήστε νέο **public** repository στο GitHub (π.χ. `ateke-photos-privacy` ή `ateke-privacy`).
2. Αντιγράψτε **μόνο τα περιεχόμενα** του φακέλου `privacy-policy` (δηλαδή τα αρχεία `index.html` και αυτό το README) στο **root** του νέου repo (όχι σε υποφάκελο).
3. Κάντε commit και push.
4. Στο repository: **Settings** → **Pages** → **Source**: επιλέξτε **Deploy from a branch**.
5. **Branch**: `main` (ή `master`), **Folder**: `/ (root)` → **Save**.
6. Μετά από 1–2 λεπτά το URL θα είναι:
   - `https://<username>.github.io/ateke-photos-privacy/`  
   (αν το repo λέγεται `ateke-photos-privacy`).

Αυτό το URL το βάζετε στο **Play Console** → **Πολιτική και προγράμματα** → **Περιεχόμενο εφαρμογής** → **Πολιτική απορρήτου**.

### Επιλογή Β: Ίδιο repo με την εφαρμογή (AtekePhotos)

1. Αν το project **AtekePhotos** είναι ήδη στο GitHub, κάντε push και τον φάκελο `privacy-policy`.
2. Στο repo: **Settings** → **Pages** → **Source**: **Deploy from a branch**.
3. **Branch**: `main` (ή `master`), **Folder**: **/ (root)** δεν δείχνει το `privacy-policy` ως αρχική σελίδα. Για να δουλέψει το URL της πολιτικής:
   - Εither μετακινήστε το `index.html` του φακέλου `privacy-policy` σε έναν φάκελο που να είναι το root του Pages (π.χ. δημιουργήστε branch `gh-pages` με μόνο το `index.html` στο root),  
   - Ή δημιουργήστε ξεχωριστό repo όπως στην **Επιλογή Α** (πιο απλό).

**Συμβουλή:** Η **Επιλογή Α** (ξεχωριστό repo `ateke-photos-privacy`) δίνει ένα απλό URL, π.χ. `https://ateke.github.io/ateke-photos-privacy/`, που είναι ιδανικό για το Play Console.
