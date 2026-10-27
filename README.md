# Lezione Interattiva sui Sistemi di Numerazione

Guida didattica interattiva sui **Sistemi di Numerazione** (**Binario**, **Ottale**, **Decimale** ed **Esadecimale / Sessadecimale**), progettata per la spiegazione frontale e il ripasso su **PC (16:9)** e per lo studio individuale su **smartphone (9:16, schermo da circa 6 pollici)**.

🌐 **Sito Live (GitHub Pages):** [https://amarte81.github.io/Sistemi-di-numerazione/](https://amarte81.github.io/Sistemi-di-numerazione/)

---

## 📖 Struttura del Progetto

La lezione è organizzata in **due parti principali** più un **Generatore Interattivo di Esercizi**:

### 🎞️ Parte 1: Slide con Concetti Essenziali ed Esempi Semplici (12 Slide)
Pensate per la spiegazione in classe e il ripasso rapido degli alunni:
1. **Cosa sono i Sistemi di Numerazione:** differenza tra cifra e numero, sistemi *Additivi* (numeri romani) vs *Posizionali* (valore assoluto e valore relativo).
2. **La Base ($b$) e la Forma Polinomiale:** legge universale $N = \sum c_i \cdot b^i$, ruolo dello zero e confronto tra le basi 2, 8, 10 e 16.
3. **Il Sistema Decimale (Base 10):** cifre `0–9`, potenze di 10 e scomposizione polinomiale.
4. **Il Sistema Binario (Base 2):** bit, nibble, byte, MSB/LSB e **simulatore interattivo a 8 bit cliccabili**.
5. **Conversione Binario → Decimale:** metodo dei pesi posizionali ($2^i$) con esempio visuale.
6. **Conversione Decimale → Binario:** metodo delle divisioni successive per 2 con lettura dei resti dal basso verso l'alto (⬆️).
7. **Il Sistema Ottale (Base 8):** cifre `0–7`, potenze di 8 e legame $8 = 2^3$ (1 cifra ottale = 3 bit).
8. **Il Sistema Esadecimale / Sessadecimale (Base 16):** cifre `0–9` e lettere `A–F` (`10–15`), legame $16 = 2^4$ (1 cifra hex = 4 bit / 1 nibble) e applicazioni reali (colori RGB, indirizzi MAC e RAM).
9. **Conversioni Rapide tra Binario, Ottale ed Esadecimale:** raggruppamenti diretti a 3 bit e a 4 bit senza passare dal decimale.
10. **Aritmetica Binaria e Overflow:** regole della somma binaria con riporto e traboccamento (overflow).
11. **Tabella Riepilogativa (0–15):** confronto immediato tra Decimale, Binario a 4 bit, Ottale ed Esadecimale.
12. **Ponte verso gli Esercizi e la Parte 2.**

### 📖 Parte 2: Spiegazione Dettagliata Completa con Esempi a Difficoltà Progressiva
Un manuale completo suddiviso in **7 capitoli tematici**, ciascuno dotato di **esempi graduati su 3 livelli (🟢 Livello 1 Base → 🟡 Livello 2 Intermedio → 🔴 Livello 3 Avanzato)**:
- **Cap. 1:** Fondamenti teorici, teorema di rappresentazione polinomiale e basi generiche.
- **Cap. 2:** Approfondimento sul Sistema Decimale (interi, zeri segnaposto e numeri con la virgola con potenze negative $10^{-k}$).
- **Cap. 3:** Approfondimento sul Sistema Binario (transistor, Bit/Byte, potenze di 2 da $2^0$ a $2^{16}$, massimo valore $2^n - 1$, calcolo del numero di bit necessari $\lceil \log_2 M \rceil$ e operazioni di shift).
- **Cap. 4:** Tutte le tecniche di conversione **Binario ↔ Decimale** (somma pesata, schema di Horner, divisioni successive per 2, sottrazione delle potenze di 2 e conversione di numeri frazionari con la virgola).
- **Cap. 5:** Il Sistema Ottale (Base 8), conversioni e caso reale dei permessi Linux (`chmod`).
- **Cap. 6:** Il Sistema Esadecimale / Sessadecimale (Base 16), conversioni tramite Nibble e ponte Binario tra Base 8 e Base 16.
- **Cap. 7:** Aritmetica binaria in colonna e rappresentazione dei numeri negativi in **Complemento a 2 (CA2)**.

### 🎲 Generatore di Esercizi di Conversione Binario ↔ Decimale
- **Generatore di numeri casuali** con scelta della direzione (`Decimale → Binario`, `Binario → Decimale` o `Mista`) e 3 livelli di difficoltà (`Base 4-5 bit`, `Intermedio 1 Byte`, `Avanzato 10 bit`).
- **Verifica immediata della risposta** inserita dallo studente con punteggio.
- **Tasto "💡 Mostra Soluzione che Applica la Conversione":** genera dinamicamente tutti i passaggi matematici (la tabella completa delle divisioni per 2 con quozienti, resti e ordine di lettura ⬆️ oppure la griglia posizionale bit per bit con sviluppo polinomiale e somma dei pesi $2^i$).
- **Risolutore libero passo-passo:** permette di inserire qualsiasi numero scelto dall'alunno o dal docente per visualizzarne lo svolgimento completo.

---

## 📱 Responsività (PC 16:9 & Smartphone 9:16 da ~6 pollici)

- **Layout Widescreen PC (16:9):** griglia affiancata a due colonne e navigazione da tastiera (`←` / `→` / `Esc`).
- **Layout Smartphone (9:16 ~6"):** impaginazione verticale ottimizzata per la larghezza mobile, pulsanti touch-friendly, tabelle scorrevoli, supporto **swipe orizzontale** tra le slide e **Simulatore 9:16 integrato** per testare la vista telefono direttamente da PC.

---

## 🚀 Utilizzo Locale

Apri direttamente il file [`index.html`](./index.html) in qualsiasi browser web moderno.
