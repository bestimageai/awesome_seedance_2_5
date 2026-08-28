# Seedance 2.5: sei ricette di prompt condivise in italiano

[Tutte le lingue](README.md) · [Indice delle 120 scene](../README.md) · [Pagina iniziale](../../README.md)

A cura del **team di bestimage.ai**. Queste sei ricette localizzate corrispondono alle scene 04, 31, 37, 43, 46 e 52 del catalogo principale. Sono traduzioni o adattamenti degli stessi scenari, non sei ulteriori prompt distinti. Non costituiscono una traduzione italiana completa del catalogo cinese. Le indicazioni creative non sono state testate; geometria precisa, testo, parlato e fisica devono essere verificati nei risultati effettivi.

Per un singolo fotogramma iniziale, usa [Seedance 2.5 da immagine a video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) (pagina in inglese). Con più risorse di riferimento, la modalità [da riferimenti a video](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) (pagina in inglese) richiede anche un video di riferimento: assegnagli esplicitamente un ruolo. L'[API GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) (pagina in inglese) è un flusso separato di generazione di immagini per preparare i fotogrammi dello storyboard, non un endpoint video. Leggi la [guida all'integrazione](../../docs/bestimage-ai-api-guide.md).

## I18N-01. Portafiltro da caffè in ceramica: un versamento controllato

Scena del catalogo: **04** · Modalità: da immagine a video · Durata: **20 secondi** · Formato: **16:9**

```text
Usa Image 1 come fotogramma iniziale: un portafiltro in ceramica blu cobalto con sei nervature esterne, un filtro di carta bianca contenente caffè macinato asciutto e una caraffa trasparente su pietra calcarea chiara. Mantieni il numero delle nervature, la sagoma senza manico, le pieghe del filtro, il contorno della caraffa e la luce mattutina da sinistra. Il prodotto è privo di marchio.

00:00–00:04: mantieni un primo piano del caffè macinato asciutto; un beccuccio a collo di cigno in acciaio inossidabile entra dall'alto a destra senza nascondere il portafiltro.
00:04–00:11: un filo d'acqua sottile e continuo descrive un piccolo cerchio all'interno del filtro. Il caffè si gonfia delicatamente; il liquido rimane sotto il bordo della carta e gocciola nella caraffa.
00:11–00:16: il getto si ferma e il beccuccio si ritira. Arretra leggermente per mostrare la caraffa che si riempie gradualmente; non ruotare il portafiltro e non modificarne le proporzioni.
00:16–00:20: mantieni una vista pulita di tre quarti del prodotto, con spazio libero a destra per aggiungere del testo in seguito.

Audio: versamento delicato, poche gocce e ambiente silenzioso della stanza; niente parlato o musica. Preserva la continuità del volume del liquido e il contatto fra gli oggetti solidi. Niente caffè fluttuante, recipienti aggiuntivi, testo leggibile, loghi, nuvole di vapore o filigrane. Cambia il colore della ceramica soltanto fornendo un nuovo fotogramma iniziale corrispondente.
```

## I18N-02. Sovracamicia reversibile: vento e movimento del tessuto

Scena del catalogo: **31** · Modalità: da riferimenti a video · Durata: **20 secondi** · Formato: **9:16**

```text
Image 1 definisce l'identità della persona adulta che posa, la cui immagine è autorizzata all'uso. Image 2 definisce una sovracamicia senza marchio color ruggine, con fodera avorio, due tasche applicate e cinque bottoni anteriori. Video 1 fornisce soltanto il lento quarto di giro e il flusso d'aria da sinistra a destra; non copiare la persona o il suo abbigliamento. Inizia con la sovracamicia aperta e la persona in piedi su una posizione segnata nello studio.

00:00–00:05: piano americano fisso; la persona solleva il lembo sinistro aperto quanto basta per mostrare la fodera, con la mano che afferra visibilmente il tessuto.
00:05–00:12: la persona lascia il lembo e compie un quarto di giro verso il lato sinistro dell'inquadratura. Un ventilatore delicato muove il lembo libero e i capelli in modo coerente verso il lato destro dell'inquadratura; spalle e cuciture delle tasche restano stabili.
00:12–00:16: il flusso d'aria si attenua. Il tessuto ricade seguendo il proprio peso anziché tornare bruscamente al suo posto.
00:16–00:20: mantieni una posa laterale rilassata, conservando la stessa altezza della camera e lo stesso obiettivo.

Audio: ventilatore discreto e movimento del tessuto; niente dialoghi. Niente inversione del capo mentre è indossato, cambio istantaneo di abbigliamento, bottoni aggiuntivi, ritocco della pelle, rimodellamento del corpo, testo, loghi o filigrane. Questa scena illustra il movimento del tessuto, non un test certificato di resistenza al vento.
```

## I18N-03. App di lettura: salvare un passaggio evidenziato

Scena del catalogo: **37** · Modalità: da riferimenti a video · Durata: **18 secondi** · Formato: **16:9**

```text
Image 1 è la schermata di lettura approvata, Image 2 la stessa schermata con un passaggio selezionato e Image 3 lo stato approvato della nota salvata. Tutti i testi visibili sono già forniti in inglese. Video 1 controlla soltanto il percorso del puntatore e i tempi dei clic. Preserva la cornice del dispositivo, la tipografia, le interruzioni di riga, la posizione di lettura e la direzione di lettura dell'interfaccia; non inventare mai il testo dell'articolo.

00:00–00:04: vista frontale fissa del dispositivo su una scrivania neutra; il puntatore si ferma accanto al passaggio mostrato in Image 2.
00:04–00:09: il puntatore seleziona quel passaggio una sola volta, seguendo Video 1. Riproduci esattamente l'evidenziazione approvata senza spostare le altre righe.
00:09–00:14: fai clic una sola volta sul controllo di salvataggio esistente e passa a Image 3. Non aggiungere notifiche temporanee, contatori, valutazioni o menu assenti dai riferimenti.
00:14–00:18: mantieni lo stato della nota salvata per consentirne l'ispezione. Niente movimento della camera o riflessi dello schermo sopra il testo.

Audio: un clic discreto per ciascun clic visibile; niente parlato, digitazione o musica. Scarta lettere alterate, controlli specchiati, evidenziazioni che si spostano, puntatori duplicati, loghi o filigrane. Per la localizzazione, fornisci tutte e tre le schermate approvate nella lingua di destinazione; non chiedere al modello video di tradurre lo schermo.
```

## I18N-04. Scioglimento della neve: ruscellamento superficiale e infiltrazione

Scena del catalogo: **43** · Modalità: da riferimenti a video · Durata: **24 secondi** · Formato: **16:9**

```text
Image 1 è una vista in sezione approvata da un docente di un letto di terreno inclinato, un sottile strato di neve e una vaschetta di raccolta trasparente sul bordo inferiore. Image 2 fornisce la sovrapposizione di frecce approvata, senza parole o numeri. Video 1 fornisce soltanto i tempi della dimostrazione a camera fissa. Mantieni costanti i confini degli strati e le dimensioni della vaschetta; è un'illustrazione didattica semplificata, non una prova sperimentale basata su misurazioni.

00:00–00:06: mostra l'intera sezione con la camera fissa. Mostra una piccola quantità d'acqua di fusione che si forma al confine fra neve e terreno.
00:06–00:13: lascia che una parte dell'acqua scenda lungo la superficie verso la vaschetta; segui le frecce superficiali di Image 2 senza aumentare la massa della neve.
00:13–00:19: mostra un'altra parte che entra nei pori superiori del terreno, seguendo le frecce discendenti approvate. Non farle attraversare istantaneamente ogni strato e non suggerire che tutti i terreni si comportino allo stesso modo.
00:19–00:24: mantieni entrambi i percorsi insieme nella stessa vista; le frecce smettono di muoversi prima della fine.

Audio: acqua sommessa e ambiente della stanza; niente narrazione o musica. Niente misurazioni inventate, inondazioni, terreno che scompare, direzioni di flusso contraddittorie, etichette, loghi o filigrane. Aggiungi didascalie esplicative verificate in postproduzione.
```

## I18N-05. Casa con cortile: mostrare il percorso reale

Scena del catalogo: **46** · Modalità: da riferimenti a video · Durata: **24 secondi** · Formato: **16:9**

```text
Image 1 fornisce la pianta approvata del piano terra di una casa stretta con cortile. Image 2 e Image 3 definiscono la stanza d'ingresso e il cortile esattamente come sono arredati. Video 1 è una visita filmata autorizzata e controlla il percorso e l'altezza della camera. Tratta la pianta come un vincolo spaziale, non come un'immagine da visualizzare. Niente viste inventate del piano superiore.

00:00–00:06: inizia appena dentro l'ingresso alla normale altezza degli occhi di un adulto, con una prospettiva naturale; mostra insieme la panca esistente e l'apertura verso il cortile.
00:06–00:14: avanza lentamente lungo il percorso di Video 1, mantenendo l'apertura in vista. Fermati prima della soglia; la camera non deve attraversare muri, mobili o vetri chiusi.
00:14–00:20: entra nel cortile attraverso l'apertura reale e fai una lenta panoramica verso l'aiuola originaria.
00:20–00:24: fermati e guarda indietro, affinché chi osserva possa comprendere il collegamento con la stanza d'ingresso.

Audio: i passi passano dalla pavimentazione interna a quella del cortile, con un'atmosfera esterna tranquilla; niente narrazione. Preserva larghezza delle porte, livelli dei pavimenti, numero dei mobili, direzione della luce solare e distanza percorsa. Niente deformazioni da ultragrandangolare, stanze aggiunte, migliorie di lusso, affermazioni sulla posizione, cartelli leggibili o filigrane.
```

## I18N-06. Trasportino per gatti: una prima visita volontaria

Scena del catalogo: **52** · Modalità: da riferimenti a video · Durata: **18 secondi** · Formato: **9:16**

```text
Image 1 definisce un gatto adulto grigio tigrato il cui materiale di riferimento è autorizzato all'uso. Image 2 definisce un trasportino morbido aperto con rivestimento blu navy, pannello laterale in rete e sportello anteriore ripiegato verso il basso. Video 1 fornisce soltanto l'avvicinamento tranquillo e il movimento di ingresso. Mantieni coerenti i segni del mantello, le dimensioni del corpo, le cuciture del trasportino, l'apertura dello sportello e il disegno della rete.

00:00–00:05: camera bassa fissa all'ingresso del trasportino. Il gatto si avvicina al trasportino vuoto e aperto, si ferma e annusa il bordo; nessuno lo spinge o lo trattiene.
00:05–00:11: il gatto entra volontariamente, prima con le zampe anteriori e poi con quelle posteriori, con contatto visibile sul pavimento. Il trasportino non si espande e non ingloba il gatto attraverso la parete laterale.
00:11–00:15: il gatto si gira una volta nello spazio disponibile e si sistema rivolto verso l'ingresso aperto.
00:15–00:18: mantieni la posa rilassata. Lascia lo sportello completamente aperto.

Audio: contatto leggero delle zampe, movimento del tessuto e ambiente tranquillo della stanza; niente fusa o suoni di disagio aggiunti. Niente sedazione, manipolazione forzata, anatomia impossibile, animali duplicati, certificazioni di sicurezza, testo, loghi o filigrane. Se il gatto di riferimento non entra spontaneamente, scegli un altro filmato autorizzato anziché prescrivere l'uso della forza.
```
