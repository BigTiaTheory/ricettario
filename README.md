# Ricettario

App web (PWA) per ricette passo dopo passo, con database online Firebase condiviso in due.

## 1. Crea il progetto Firebase
1. Vai su https://console.firebase.google.com → Aggiungi progetto.
2. **Authentication** → Inizia → metodo "Email/password" → Abilita.
3. Authentication → Users → **Aggiungi utente**: crea due account (tu e la tua ragazza) con email e password.
4. **Firestore Database** → Crea database (modalità produzione, regione europea, es. `eur3`).
5. Firestore → scheda **Regole**: incolla il contenuto di `firestore.rules`, sostituisci le due email con le vostre → Pubblica.
6. Impostazioni progetto (ingranaggio) → Le tue app → **Web** (</>) → registra l'app → copia la configurazione.
7. Incolla i valori in `firebase-config.js`.
8. Authentication → Settings → **Domini autorizzati** → aggiungi `TUO-UTENTE.github.io`.

## 2. Pubblica su GitHub Pages
Carica tutti i file (cartella `icons` inclusa) nel repository, poi Settings → Pages → branch `main`, `/ (root)`.

## 3. iPhone
Apri l'indirizzo in Safari → Condividi → "Aggiungi alla schermata Home". Accedi con la tua email.
