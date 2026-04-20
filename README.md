# 📘 InclusivAI-tool: Prototipo

Questo repository contiene il prototipo di un'applicazione basata su Intelligenza Artificiale Generativa (LLM), progettata per l'integrazione nelle piattaforme di editoria digitale. 

L'obiettivo di **InclusivAI-tool** è permettere a docenti e studenti di personalizzare i contenuti didattici in tempo reale, garantendo inclusività e accessibilità con un singolo click.

## 🚀 Funzionalità Principali
- **✨ Semplificazione DSA:** Rielaborazione del testo per studenti con disturbi specifici dell'apprendimento. Output ottimizzato per alta leggibilità e scaricabile in **PDF**.
- **🌍 Adattamento NAI:** Facilitazione linguistica per alunni stranieri (italiano L2 - Livello A2). Include glossario e testi semplificati, scaricabile in **PDF**.
- **🗺️ Mappe Concettuali:** Estrazione automatica della gerarchia logica dei contenuti e generazione di schemi riassuntivi in **PDF**.
- **📝 Generazione Test:** Creazione istantanea di verifiche (Scelta multipla e Vero/Falso) complete di soluzioni, scaricabile in formato **Microsoft Word (.docx)** per consentire l'editing del docente.

## 🛠️ Architettura Tecnica
- **Linguaggio:** Python
- **Framework:** Streamlit
- **Modello IA:** Google Gemini 1.5 Flash (Multimodale: analizza Testo, Immagini e PDF)
- **Sicurezza:** Gestione delle chiavi API tramite *Streamlit Secrets* per garantire l'integrità del sistema.

## 📂 Struttura del Progetto
- `app.py`: Il cuore logico dell'applicazione.
- `requirements.txt`: Elenco delle dipendenze necessarie per il deployment.
- `README.md`: Documentazione tecnica del progetto.

## 👤 Sviluppo e Visione
Ideato e sviluppato da **Simona Scanni**, esperta in didattica inclusiva e innovazione tecnologica. Il progetto nasce per colmare il divario tra i contenuti standard dei libri di testo e le necessità specifiche degli studenti BES (Bisogni Educativi Speciali).
