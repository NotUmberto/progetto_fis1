# Caso d'Uso: Sfogliare Catalogo
## Breve Descrizione: 
Questo use case permette agli utenti di visualizzare i contenuti presenti sulla piattaforma.
## Attori primari: 
- Utente
## Attori secondari: 
- Server 
## Precondizioni: 
Nessuna.
## Sequenza degli eventi principale:
1. L'utente clicca sulla sezione "sfoglia catalogo".
2. Viene mostrato a schermo l'elenco dei contenuti presenti sulla piattaforma.
3. Per ciascun film viene mostrata:
    - il titolo;
    - la copertina;
    - la descrizione.
4. L'utente clicca su una copertina.
5. Vengono mostrate tutte le informazioni sul contenuto, compreso la disponibilita relativa all'abbonamento dell'utente, con possibilita di vederlo cliccando sul pulsante "visualizza" e collegandoci allo use case (`"Visualizza Base"` o `"Visualizza Premium"`).

## Postcondizioni: 
Nessuna.  
## Sequenza degli eventi alternativa: 
`AssenzaDiContenuti`

