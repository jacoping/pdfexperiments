# Appunti generatore fuoriporta:


## TODO v1
--

**FUNZIONALITA'**
- [x]	Inserire un'opzione per avere i colori scambiati testo/sfondo.
- [x]	Aggiungere larghezza massima campi.
- [x] Regolare interlinea su campo destro (nomi e specifiche)
- [x]	Le strutture devono diventare un menu a discesa. È semplice perché con "onchange" vengono popolate delle variabili.
- [x] Bugfix: in "compilazione libera" i text field delle strutture non devono essere bloccati
- [x] Separare html da js
- [x] Nei campi liberi di "funzione" dovrebbe essere imposto lowercase
- [x] Funzioni con menu a discesa, con possibilità di inserimento manuale
- [x] Inserire opzione per nome oppure specifica sui campi nome
- [x] Cambiare funzionamento di nextpage e prevpage lavorando sulla visualizzazione e non sulla compilazione
- [x] Riscrivere inizializzazione in questo modo:
      1. Si inizializza tutto il form, vuoto
      2. Si inizializza eventualmente una struttura, o anche no.
      3. Quando si cambia il selettore delle strutture non viene ricaricato tutto.
- [x] Implementare underscore => NBS per nomi
- [x] Implementare underscore => NBS per strutture
- [x] Modificare layout spostando i due bottoni "CREA PDF" sopra l'anteprima
- [x] Implementare next/prev con frecce
- [x] Correggere NEUROFARBA in liste
- [x] Risolvere overflow dei nomi in alto (dopo aver calcolato l'altezza della parte destra eliminare via via le righe superiori finché non risulta sotto un certo valore)
- [ ] BUGFIX I select non funzionano da mobile
- [ ] Dare una sistemata al layout mobile di modo che possa andare in produzione anche così
- [ ] Sostituire "Scarica il pdf" con un button
- [ ] Aggiungere qr code per giombetti
      https://github.com/soldair/node-qrcode
      https://github.com/papnkukn/qrcode-svg (sembra il più semplice)
      https://github.com/davidshimjs/qrcodejs
- [ ] Separare html da js: eliminare js in html e togliere id e classes dalle funzioni
- [ ] Aggiungere "loading" o "qualcosa non ha funzionato" che rimanga nel caso l'antemprima non si carichi per qualsiasi motivo.
- [ ] Aggiungere loadbar quando carica il CSV


**LAYOUT BOOTSTRAP**
- [ ] Spostare titolo in alto su mobile
- [ ] Controllare visualizzazioni intermedie (ipad)
- [ ] Va benissimo come si vedono i select dei nomi da mobile. Da desktop devono vedersi ben larghi.
- [ ] Implementare con uno script locale lo switch singolo/multiplo
- [ ]






**LAYOUT FUORIPORTA**
- [x] Aggiungere annotazioni nella riga in basso (sicuramente "creato con..." la data).

- [x] Cambiare corpi
- [x] Regolare interlinea tra strutture e funzioni
- [x] Regolare accapo e eventuale interlinea su campo sinistro (strutture + funzioni)


**LAYOUT SITO**
- [ ] Spostare il titolo fuori dalla scheda
- [ ] Spostare aggiorna l'anteprima sopra l'anteprima
- [ ] Spostare "carica il pdf" sotto l'anteprima

---

## TODO v2
- [ ] Implementare auto update come qui: http://pdfkit.org/demo/browser.html
- [ ] Il pdf deve essere impaginato in un A4?
- [ ] La preview deve essere inclusa in un fuoriporta intero?
- [x] Aggiorna fuoriporta con INVIO
- [ ] Inserire nei campi testo invece di testo vero dei suggerimenti che poi spariscono (svincolare primo render del pdf dai contenuti dei campi)
