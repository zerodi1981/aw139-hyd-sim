# Simulatore impianto idraulico ispirato all'AW139 – ATA 29

Simulatore **amatoriale e non ufficiale** che si ispira all'impianto idraulico di un elicottero bimotore della classe AW139 (ATA 29 – Hydraulic Power). È una ricostruzione semplificata e non verificata, **da considerare un gioco**.

**▶ Apri il simulatore:** https://zerodi1981.github.io/aw139-hyd-sim/

## Cosa simula

- **Sinottico HYD dell'MFD**: pressioni, temperature, livelli dei serbatoi, pompe, valvole SOV / UTIL SOV / TRSOV, servo del rotore principale e di coda, indicazioni LDG GEAR NORM/EMER.
- **CAS** con cautions ambra, messaggi di manutenzione, MASTER CAUTION / MASTER WARNING con conferma e avviso acustico.
- **Pannello HYD**: ELECT PUMP (105/90 bar, timer 2 min, inibita in volo), spie PRESS e TEMP, selettore SOV con protezione e interlock, LAMP TEST.
- **Pannello LDG GEAR**: spie NOSE/LH/RH, leva, EMERG DOWN con protezione.
- **Logiche dei microswitch di livello** dei PCM (50% / 28% / 22%) e isolamento automatico di utility e rotore di coda.
- **Avarie**: pompe (usura con case drain, rottura shear shaft, compensatore bloccato), perdite in diversi punti, surriscaldamento (isolabile, non isolabile, falso allarme), intasamento progressivo dei filtri con by-pass sul ritorno, servo in by-pass, shuttle valve bloccata.
- **Manutenzione**: indicatori meccanici a scatto con reset, livello visivo FULL/ADD, rabbocco, banco idraulico a terra.
- **Scenari pronti** di funzionamento normale e di avaria.

## Come si usa

Apri il link qui sopra, oppure scarica `index.html` e aprilo con un doppio clic in qualsiasi browser moderno (Chrome, Edge, Firefox, Safari). Funziona anche offline e non richiede installazioni.

## Avviso

Questo simulatore è una **ricostruzione amatoriale e semplificata**, frutto dell'interpretazione personale dell'autore. Logiche e valori **non sono stati verificati** e possono essere incompleti o diversi dalla realtà; molti valori sono stimati.

- **Va considerato un gioco**: non è uno strumento di addestramento e non bisogna allenarsi o studiare su questo simulatore.
- Non è prodotto, verificato né approvato da Leonardo Helicopters, da autorità aeronautiche o da alcun altro ente.
- Non può essere usato per addestramento, manutenzione, ricerca guasti, decisioni operative o qualsiasi scopo ufficiale: per questo vale esclusivamente la documentazione ufficiale approvata e l'addestramento certificato.

AW139 è un marchio dei rispettivi proprietari ed è citato a solo scopo descrittivo.

## Licenza

© 2026 Scarascia Simone – distribuito con licenza [Creative Commons BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.it).

[![CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.it)

- ✅ Puoi usarlo e condividerlo liberamente, così com'è, citando l'autore.
- ❌ Non puoi venderlo né usarlo a fini commerciali.
- ❌ Non puoi distribuirne versioni modificate.
- ❌ Non puoi rimuovere o cambiare il nome dell'autore.

Testo completo nel file [LICENSE](LICENSE).

---

Simulatore creato da **Scarascia Simone**
