---
title: 'Anteprima Flutter GPU, miglioramenti web e molto altro!'
description: 'presentiamo Flutter 3.24 e Dart 3.5'
pubDate: 'Aug 22 2024'
heroImage: 
  src: '/flutter.gif'
  alt: 'flutter'
tags: ['mobiledev', 'development', 'flutter', 'multiplatform']
series: "mobile"
---

Flutter, il toolkit UI open source di Google, ha visto una rapida evoluzione, offrendo agli sviluppatori un framework robusto per creare applicazioni compilate in modo nativo su dispositivi mobili, web e desktop da un'unica base di codice. Con l'introduzione di Flutter 3.24 , il framework apporta diversi aggiornamenti e funzionalità importanti progettati per migliorare l'esperienza di sviluppo, aumentare le prestazioni ed espandere le sue capacità multipiattaforma.

In questo articolo approfondiremo le caratteristiche principali di Flutter 3.24, esaminando in che modo queste nuove funzionalità possono apportare vantaggi agli sviluppatori e perché questa versione segna un traguardo importante per la community di Flutter.

## Caratteristiche principali e miglioramenti in Flutter 3.24

**Miglioramenti significativi nel rendering GPU:** <br>
Uno dei punti salienti di Flutter 3.24 è il miglioramento del rendering GPU (Graphics Processing Unit), che è fondamentale per le applicazioni che richiedono animazioni fluide e grafica visivamente intensiva. Il motore di rendering aggiornato ottimizza il modo in cui vengono elaborati i dati grafici, con conseguenti transizioni più fluide, lag ridotto e un'esperienza utente più reattiva. Questo miglioramento è particolarmente cruciale per gli sviluppatori che lavorano su app critiche per le prestazioni, come giochi o applicazioni multimediali, in cui la velocità e la qualità del rendering sono fondamentali.

### Incorporamento multi-vista: una nuova dimensione di flessibilità
L'introduzione dell'incorporamento multi-view in Flutter 3.24 è una svolta per gli sviluppatori che lavorano su applicazioni complesse. Consente l'incorporamento di più istanze Flutter all'interno di una singola app, ciascuna delle quali gestisce viste o sezioni diverse. Ciò è particolarmente utile per le app che richiedono una navigazione complessa o devono visualizzare più flussi di contenuti contemporaneamente, come dashboard o applicazioni multi-tasking.

L'incorporamento multi-view migliora la gestione delle risorse assicurando che ogni istanza operi in modo indipendente ma efficiente all'interno della stessa app. Ciò porta a prestazioni più snelle, anche quando si gestiscono più viste con molti dati o interfacce utente complesse.

### Integrazione Dart 3.5: aumento dell'efficienza dello sviluppo
Il rilascio di Dart 3.5 insieme a Flutter 3.24 introduce una serie di nuove funzionalità e ottimizzazioni che migliorano sia l'esperienza di sviluppo che le prestazioni delle app Flutter. Dart 3.5 offre un'inferenza di tipo migliorata, rendendo più semplice scrivere codice conciso e gestibile. I miglioramenti nel processo di compilazione riducono i tempi di compilazione, consentendo agli sviluppatori di iterare in modo più rapido ed efficiente.

Dart 3.5 include anche nuove funzionalità del linguaggio come pattern matching e record types, che semplificano la codifica e consentono agli sviluppatori di scrivere codice più espressivo e robusto. Contribuisce a un processo di sviluppo più snello, aiutando gli sviluppatori a creare app di alta qualità più velocemente e con meno bug.

### Strumenti di sviluppo avanzati per un'esperienza di sviluppo migliorata
debug e profilazione più potenti. Fornisce informazioni più approfondite sulle prestazioni delle app, consentendo agli sviluppatori di tracciare l'utilizzo della memoria, monitorare i tempi di rendering dei frame e identificare potenziali colli di bottiglia in modo più efficace. I DevTools migliorati sono essenziali per ottimizzare le prestazioni delle app, assicurando che le app funzionino in modo fluido ed efficiente su tutte le piattaforme.


Flutter 3.24 è dotato di DevTools avanzati che offrono agli sviluppatori strumenti di debug e profilazione più potenti. Fornisce informazioni più approfondite sulle prestazioni delle app, consentendo agli sviluppatori di tracciare l'utilizzo della memoria, monitorare i tempi di rendering dei frame e identificare potenziali colli di bottiglia in modo più efficace. I DevTools migliorati sono essenziali per ottimizzare le prestazioni delle app, assicurando che le app funzionino in modo fluido ed efficiente su tutte le piattaforme.

![](src/content/blog/foto/devtools.webp)




## Widget SelectionArea aggiornato
Da una prospettiva tecnica, il widget SelectionArea in Flutter 3.24 è stato migliorato con nuovi gesti che migliorano l'usabilità della selezione del testo. Ad esempio, il widget ora supporta tripli clic per selezionare interi paragrafi e funzionalità di trascinamento per selezionare migliorata. Consente una selezione del testo più precisa, particolarmente utile nelle applicazioni in cui la modifica o la manipolazione del testo è una funzionalità chiave.

L'introduzione di questi gesti riflette anche l'impegno costante di Flutter nel creare un'esperienza utente fluida e intuitiva attraverso diversi metodi di input, tra cui mouse, tocco e tastiera.

## Miglioramenti del plugin Shared Preferences
Flutter 3.24 introduce due aggiornamenti significativi al plugin Shared Preferences: SharedPreferencesAsync e SharedPreferencesWithCache.

- **SharedPreferencesAsync**: migliora le prestazioni dell'applicazione scaricando le operazioni di preferenza sui thread in background. Ciò è particolarmente utile in scenari in cui frequenti operazioni di lettura/scrittura potrebbero altrimenti bloccare il thread dell'interfaccia utente, portando a un'esperienza utente più fluida.
- **SharedPreferencesWithCache**: riduce la frequenza di accesso al disco memorizzando nella cache le preferenze, il che velocizza le operazioni di lettura. È ideale per applicazioni con impostazioni o preferenze a cui si accede di frequente ma che vengono aggiornate di rado.

## Rendering delle immagini migliorato
Un altro importante aggiornamento tecnico in Flutter 3.24 è il cambiamento nel FilterQuality predefinito per le immagini. Il valore predefinito è stato spostato da Low a Medium , il che aiuta a impedire che le immagini appaiano pixelate quando vengono ridimensionate in modo significativo. Non solo migliora l'aspetto visivo delle immagini, ma ottimizza anche le prestazioni di rendering bilanciando qualità e velocità.

Per gli sviluppatori che gestiscono un gran numero di immagini o hanno bisogno di visualizzarle a diverse risoluzioni, questo aggiornamento garantisce che le loro applicazioni forniscano immagini nitide e di alta qualità senza compromettere le prestazioni.


<section class="mt-16">
    <div class="twitter-container">
    <div style="text-align: center;">
        <!-- Tweet 1 -->
        <blockquote class="twitter-tweet">
            <p lang="en" dir="ltr">Get ready to raise the bar for multi-platform graphics rendering and performance. 🚀<br><br>Flutter 3.24 and Dart 3.5 are here → <a href="https://t.co/CjUw5HWy2j">https://t.co/CjUw5HWy2j</a> <a href="https://t.co/ssiOzCsTUC">pic.twitter.com/ssiOzCsTUC</a></p>&mdash; Flutter (@FlutterDev) <a href="https://twitter.com/FlutterDev/status/1820945477308731785?ref_src=twsrc%5Etfw">August 6, 2024</a>
        </blockquote>
        <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
</section>


## Altre caratteristiche degne di nota in Flutter 3.24
 ### Barre delle applicazioni dinamiche con nuovi sliver

In Flutter 3.24, gli sviluppatori hanno accesso a un set di nuovi sliver che introducono comportamenti dinamici nelle barre delle app, offrendo maggiore flessibilità e facilità d'uso rispetto agli approcci tradizionali. Questi nuovi sliver includono:

- **SliverFloatingHeader:** consente alle barre delle applicazioni di fluttuare sul contenuto mentre l'utente scorre, offrendo un'esperienza fluida e visivamente coinvolgente.

- **PinnedHeaderSliver**: mantiene la barra delle app bloccata in cima allo schermo, anche quando l'utente scorre verso il basso. Questa funzionalità è particolarmente utile per ricreare effetti simili a quelli visti nelle Impostazioni iOS, dove l'intestazione rimane sempre visibile.

- **SliverResizingHeader**: consente il ridimensionamento dinamico della barra delle applicazioni in base alla posizione di scorrimento, consentendo design più interattivi e reattivi.

Fornisce un'API più semplice rispetto ai vecchi SliverPersistentHeader e SliverAppBar , rendendo più semplice implementare comportamenti sofisticati della barra delle applicazioni con codice minimo. Inoltre, è disponibile un codice di esempio per aiutarti a iniziare rapidamente con questi nuovi strumenti.

## Miglioramenti della libreria di Cupertino

La libreria Cupertino, nota per aver portato componenti in stile iOS in Flutter, ha ricevuto diversi aggiornamenti degni di nota in Flutter 3.24. Un miglioramento fondamentale è il feedback tattile migliorato per i pulsanti CupertinoActionSheet , che ora offrono un'esperienza più tattile e reattiva. Anche la dimensione e il peso del carattere di questi pulsanti sono stati modificati per allinearsi meglio all'estetica nativa di iOS, migliorando l'esperienza utente complessiva.

Inoltre, sono state aggiunte nuove proprietà di messa a fuoco a CupertinoButton e gli sviluppatori ora possono personalizzare il colore di un CupertinoTextField disabilitato . Questi aggiornamenti non solo migliorano l'usabilità e l'attrattiva visiva dei widget di Cupertino, ma forniscono anche agli sviluppatori più opzioni di personalizzazione per creare applicazioni raffinate, simili a iOS.

## Introduzione dei widget TreeView e CarouselView

Flutter 3.24 introduce due nuovi potenti widget che ampliano le funzionalità dell'interfaccia utente del framework:

- **TreeView Widget:** parte del pacchetto two_dimensional_scrollables, il widget TreeView è progettato per creare strutture ad albero scorrevoli che possono espandersi in più direzioni. È ideale per visualizzare dati gerarchici o strutture di navigazione complesse. Include anche TreeSliver, che consente alberi scorrevoli monodimensionali, abbinandosi all'API TreeView per un'integrazione senza soluzione di continuità.

- **Widget CarouselView:** seguendo le linee guida di Material Design, il widget CarouselView offre un elenco scorrevole in cui gli elementi si ridimensionano dinamicamente quando entrano ed escono dalla finestra di visualizzazione. Conferisce un tocco elegante e interattivo ai caroselli, rendendoli più coinvolgenti e visivamente accattivanti per gli utenti.

I nuovi widget sono corredati da esempi che aiutano gli sviluppatori a familiarizzare rapidamente con le loro funzionalità, consentendo di integrare facilmente questi elementi in progetti nuovi ed esistenti.



