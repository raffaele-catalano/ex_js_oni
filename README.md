# Esercitazione Javascript

> un semplice (ma non scontato) esercizio per ripassare e potenziare alcuni concetti di `Javascript`.

## Tecnologie: 
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=astro,js,css,html,md,github&perline=7" />
  </a>
</p>


## Requisiti:
- Tempo libero (non basta mai).

## Installazione:
1. scaricare la cartella;
2. estrarre il contenuto dell'archivio;
3. aprire la cartella in un `IDE`;
4. nel terminale dell'`IDE` lanciare il comando
```
npm install
```
5. (al termine dell'operazione) nel terminale lanciare il comando
```
npm run dev
```

## Scopo del Progetto:
Realizzare una "piattaforma" che consente agli utenti di effettuare il `sign-in` ed accedere ad alla sua "area personale".

## Note di Design:
Il design della "piattaforma" dev'esser statico, non un lavoro completo bensì un punto di partenza.
<br>
1. Aggiungere una icona "eye" per mostrare/nascondere la password in fase di digitazione;
2. Gli input devono avere lo stile nei vari status: `onFocus` `onBlur`;
3. Il pulsante deve avere lo stile anche in `onHover`;
4. Non esiste una `API` da montare, immaginare di fare `sign-in` con delle credenziali;
5. In caso di credenziali di accesso non corrette, impostare un avviso di errore per 5 secondi, in modo da dare all'utente la percezione di ciò che sta facendo;
6. Creare dei `json mocked` che andranno a definire la struttura dei dati mostrati nella `view landing`.