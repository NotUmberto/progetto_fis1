# Caso d'Uso: Sfogliare il catalogo

## Breve Descrizione:
Permette all'utente di visualizzare i film e le serie TV presenti nel catalogo.

## Attori primari:
- Utente

## Attori secondari:
- Nessuno

## Precondizioni:
- Nessuna.

## Sequenza degli eventi principale:
1. L'utente accede alla sezione "Catalogo".
2. Il sistema recupera i contenuti presenti nel catalogo.
3. Il sistema mostra l'elenco dei film e delle serie TV.
4. Per ogni contenuto vengono mostrati:
   - titolo;
   - copertina;
   - descrizione;
   - eventuale indicazione del tipo di abbonamento richiesto.
5. L'utente seleziona un contenuto.
6. Il sistema mostra le informazioni dettagliate del contenuto.
7. Se l'utente è registrato e il contenuto è disponibile per il suo abbonamento, può avviare:
   - "Visualizzazione film/serie TV base"; oppure
   - "Visualizzazione film/serie TV premium".

## Postcondizioni:
- Il catalogo è stato visualizzato; oppure
- sono state mostrate le informazioni dettagliate di un contenuto.

## Sequenza degli eventi alternativa:

### A1. Catalogo vuoto
1. Il sistema non trova contenuti nel catalogo.
2. Il sistema mostra un messaggio che informa l'utente che il catalogo è vuoto.

### A2. Errore nel caricamento
1. Il sistema non riesce a recuperare il catalogo.
2. Il sistema mostra un messaggio di errore.
3. L'utente può ritentare il caricamento.

### A3. Contenuto non disponibile per l'utente
1. L'utente seleziona un contenuto non incluso nel suo abbonamento.
2. Il sistema mostra le informazioni del contenuto.
3. Il sistema informa l'utente che non può visualizzarlo con il suo abbonamento.