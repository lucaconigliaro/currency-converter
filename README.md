# 💱 Convertitore di Valuta

Un semplice **convertitore di valuta** sviluppato in **React** che utilizza l’API pubblica di [Frankfurter.app](https://www.frankfurter.app/) per ottenere i tassi di cambio in tempo reale.  
L’interfaccia è costruita con **Bootstrap** per uno stile pulito e responsive.

---

## 🚀 Funzionalità

- 🔄 Conversione immediata tra due valute
- 🌍 Caricamento automatico di tutte le valute disponibili
- 🔁 Pulsante per **invertire** rapidamente le valute
- ⚡ Conversione tramite **API Frankfurter**
- 🎯 Gestione errori e risultati chiari a schermo

---

## 🛠️ Tecnologie Utilizzate

- ⚛️ **React**  
- 💅 **Bootstrap 5** (classi CSS per layout e stile)  
- 🌐 **Axios** (per le chiamate HTTP)  
- 💱 **Frankfurter API** (dati di conversione)

---

## 📦 Installazione e Avvio

Clona il progetto e installa le dipendenze:

```bash
git clone https://github.com/tuo-username/currency-converter.git
cd currency-converter
npm install
npm run dev
```
Poi apri il browser su http://localhost:5173 (o la porta indicata da Vite).


⸻

⚙️ Come Funziona
	1.	All’avvio, l’app carica automaticamente l’elenco di valute tramite https://api.frankfurter.app/currencies.
	2.	L’utente inserisce un importo, sceglie le valute di partenza e arrivo.
	3.	Premendo Converti, viene eseguita una chiamata a
https://api.frankfurter.app/latest?amount={amount}&from={from}&to={to}.
	4.	Il risultato viene mostrato a schermo in modo chiaro e immediato.

⸻

🧩 Esempio di Utilizzo
Importo: 100  
Da: EUR  
A: USD  

👉 Risultato: 100 EUR = 108.72 USD


⸻

📚 API Reference

	•	Frankfurter API Docs

⸻

💡 Note

	•	Se le due valute selezionate sono uguali, l’app restituisce direttamente l’importo inserito.
	•	In caso di errore nella chiamata API, il risultato viene resettato.
