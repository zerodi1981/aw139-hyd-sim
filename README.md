# Simulatore impianto idraulico AW139 – ATA 29

Simulatore didattico **non ufficiale** dell'impianto idraulico dell'elicottero AW139 (ATA 29 – Hydraulic Power), pensato per lo studio e il ripasso.

**▶ Apri il simulatore:** https://zerodi1981.github.io/aw139-hyd-sim/

## Cosa simula

- **Sinottico HYD dell'MFD**: pressioni, temperature, livelli dei serbatoi, pompe, valvole SOV / UTIL SOV / TRSOV, servo del rotore principale e di coda, indicazioni LDG GEAR NORM/EMER.
- **CAS** con cautions ambra, messaggi di manutenzione, MASTER CAUTION / MASTER WARNING con conferma e avviso acustico.
- **Pannello HYD**: ELECT PUMP (105/90 bar, timer 2 min, inibita in volo), spie PRESS e TEMP, selettore SOV con protezione e interlock, LAMP TEST.
- **Pannello LDG GEAR**: spie NOSE/LH/RH, leva, EMERG DOWN con protezione.
- **Logiche dei microswitch di livello** dei PCM (50% / 28% / 22%) e isolamento automatico di utility e rotore di coda.
- **Avarie**: pompe (usura con case drain, rottura shear shaft, compensatore bloccato), perdite in diversi punti, surriscaldamento (isolabile, non isolabile, falso allarme), intasamento progressivo dei filtri con by-pass sul ritorno, servo in by-pass, shuttle valve bloccata.
- **Manutenzione**: indicatori meccanici a scatto con reset, livello visivo FULL/ADD, rabbocco, banco idraulico a terra.
- **Scenari pronti** che riproducono i casi di funzionamento e avaria descritti nella pubblicazione di addestramento.

## Come si usa

Apri il link qui sopra, oppure scarica `index.html` e aprilo con un doppio clic in qualsiasi browser moderno (Chrome, Edge, Firefox, Safari). Funziona anche offline e non richiede installazioni.

## Avviso

Questo progetto **non è prodotto, approvato né validato** da Leonardo Helicopters o da alcuna autorità aeronautica.
Le logiche riproducono quanto descritto nella pubblicazione di addestramento ATA 29; alcuni valori non presenti nel manuale sono stimati e indicati come tali nella pagina.

Non sostituisce l'addestramento certificato e **non deve essere usato** per manutenzione, ricerca guasti, decisioni operative o qualsiasi scopo ufficiale. Per ogni attività ufficiale fare riferimento esclusivamente alla documentazione approvata e in vigore (AMM / IETP, RFM, procedure aziendali).

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

Simulatore creato da **Scarascia Simone** · ☕ [Offrimi un caffè, se vuoi](https://www.paypal.me/scarasciasimone)
