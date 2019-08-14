---
title: Sviluppo WordPress
parent: Risorse utili
nav_order: 3
---

# Sviluppo WordPress
Gran parte del mio interesse è relativo allo sviluppo con WordPress, non soltanto lo reputo un potente CMS ma mi piace molto usarlo come framework di partenza per lo sviluppo dei miei progetti web. Tornerò sicuramente a strutturare meglio questa sezione ma al momento spero che questo elenco di strumenti che uso possa esserti utile.

PS: non ti dimenticare che se usi Visual Studio Code come editor di base puoi trovare [molte estensioni utili](estensioni-vscode.md) nella pagina dedicata.

## Plugin
Generalmente non sono un amante di plugin per quanto riguarda lo sviluppo WordPress ma questi tre hanno scatenato il mio interesse e si sono dimostrati più e più volte incredibilmente utili per il mio lavoro.

* [Simply Show Hooks](https://wordpress.org/plugins/simply-show-hooks/) - anche se non è stato più aggiornato questo plugin continua a fare egregiamente il suo lavoro. Molto utile soprattutto per chi lavora con Genesis, WooCommerce o un qualsiasi altro tema/plugin che fa largo uso degli Hook WordPress ritengo che questo sia un plugin assolutamente da installare perché permette di identificare facilmente quale sia l'Hook più idoneo per aggiungere le proprie funzioni oppure per rimuovere quelle inserite.
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) - creato da uno dei più bravi sviluppatori WordPress in circolazione, questo plugin permette di conoscere tutto quello di cui hai bisogno durante l'esecuzione delle tue pagine. E quando dico tutto è proprio tutto, dagli errori fino al tempo di esecuzione delle query.
* [Debug Toolkit](https://wordpress.org/plugins/debug-toolkit/) - plugin che ho conosciuto soltanto recentemente, permette di velocizzare il processo di debug utilizzando strumenti che non richiedono neanche la configurazione di xDebug come Kint. Oltre a questo la pagina che si genera quando si commente un errore è **incredibilmente dettagliata**, provare per credere.

## Librerie
* [CMB2](https://github.com/CMB2/CMB2) - Interessantissima libreria che permette di mettere da parte interfacce grafiche come quelle proposte da ACF. Da anni la utilizzo per la creazione di custom fields, pagine opzioni e qualsiasi altro metadato che devo aggiungere a una classica installazione WordPress. L'unico "competitor" che ho trovato per questa libreria è il framework [Meta Box](https://metabox.io/) (soprattutto perché aiuta anche nella creazione di blocchi Gutenberg) ma se devi creare semplici campi CMB2 non ha rivali!
