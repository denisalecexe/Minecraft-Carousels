# Minecraft (mobs) Carousels

Un progetto ideato per creare un carosello di immagini continuo e infinito che mostra molti dei mob presenti nel videogioco Minecraft. Questo lavoro nasce sia dalla passione per il gioco, sia dalla voglia di mettermi alla prova nella realizzazione del mio primo carosello dinamico.

L'interfaccia riprende fedelmente l'identità visiva del gioco: lo sfondo della pagina richiama il profondo viola del portale del Nether, mentre i dettagli e i font pixelati ricreano la tipica atmosfera sandbox.

---

## Funzionalità principali
* **Scorrimento Infinito Automatico**: Un flusso continuo di immagini che si sposta fluidamente da destra a sinistra senza interruzioni.
* **Interattività Hover**: Al passaggio del mouse, l'animazione entra in pausa per permettere una consultazione comoda.
* **Effetto Focus Dinamico**: Il mob selezionato si ingrandisce e torna a piena opacità, mentre gli altri mob della pellicola si riducono di scala e si dissolvono parzialmente sullo sfondo.
* **Stile Pixel-Art Coerente**: Utilizzo di font personalizzati e ombreggiature (`text-shadow`) studiate per richiamare la UI originale di Minecraft.

---

## Tecnologie Utilizzate
* **HTML5**: Utilizzato per strutturare gli elementi del carosello e la griglia semantica della pagina.
* **CSS3**: Utilizzato per la gestione del layout, degli effetti di transizione dinamici e delle `@-rules` (`@keyframes` e `@font-face`) necessarie per lo scrolling infinito e il caricamento dei font.

---

## Struttura del progetto
``` txt
Minecraft-Carousels
├── src/
│   ├── assets/
│   │   ├── favicon/
│   │   │   └── craftin-table-icon.ico
│   │   ├── font/
│   │   │   ├── pixel3/
│   │   │   │   └── pixel.ttf
│   │   │   └── Pixelon/
│   │   │       └── Pixelon.ttf
│   │   ├── img/
│   │   │   ├── black-skeleton.png
│   │   │   ├── blaze.png
│   │   │   ├── chiken.png
│   │   │   ├── cow.png
│   │   │   ├── creeper.png
│   │   │   ├── delphin.png
│   │   │   ├── donkey-house.png
│   │   │   ├── ender-dragon.png
│   │   │   ├── enderman.png
│   │   │   ├── ghast.png
│   │   │   ├── iron-golem.png
│   │   │   ├── llama.png
│   │   │   ├── pig.png
│   │   │   ├── polar-bear.png
│   │   │   ├── rabit.png
│   │   │   ├── sheep.png
│   │   │   ├── skeleton.png
│   │   │   ├── slime.png
│   │   │   ├── spider.png
│   │   │   ├── Steve.png
│   │   │   ├── turtle.png
│   │   │   ├── vilager.png
│   │   │   ├── witch.png
│   │   │   ├── wolf.png
│   │   │   └── zombie.png
│   │   └── logo/
│   │       └── minecraft-logo.png
│   ├── styles/
│   │   └── style.css
│   └── index.html
├── LICENSE
└── README.md
```

---

## Installazione e Utilizzo
Basta scaricare il codice aprilo in web per poter vedere il carosello funzionante.

Istruzioni passo passo su come installare e configuare il progetto in locale.

1. Clonare il repository_
``` bash
git clone [https://github.com/tuo-username/Minecraft-Carousels.git](https://github.com/tuo-username/Minecraft-Carousels.git)
```

2. Accedere alla cartella del progetto:
``` bash
cd Minecraft-Carousels
```

3. Avviare il progetto:
Non sono necessarie dipendenze esterne.
È sufficente aprire il file `/src/index.html` direttamente nel browser o avviarlo tramite un server locale (ad esempio l'estensione *Live Server* di *VS Code*).

---

## Contribuire al progetto
Le pull request sono benvenute.
Per modifiche sostanziali, si prega di aprire prima una segnalazione per discutere di cosa si desidera modificare.

---

## Autore
* **Denis (Dharelyx)** - Sviluppatore Junior appassionato di codice e problem solving.
* Progetto completato come parte del mio percorso.
