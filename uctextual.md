# Caso d'Uso: Sfogliare Catalogo
## Breve Descrizione: 
Permette agli utenti di visualizzare i film e le serie TV presenti sulla piattaforma.
## Attori primari: 
- Utente
## Attori secondari: 
Nessuno.
## Precondizioni: 
Nessuna.
## Sequenza degli eventi principale:
1. L'utente accede alla sezione cliccando su "Catalogo".
2. Viene mostrato a schermo l'elenco dei contenuti presenti sulla piattaforma.
3. Per ciascun contenuto viene mostrata:
    - il titolo;
    - la copertina.
4. L'utente seleziona un contenuto cliccando sulla copertina.
5. Vengono mostrate tutte le informazioni sul contenuto, compreso la disponibilita relativa all'abbonamento dell'utente.
6. Se l'utente puo visualizzare il contenuto allora e presente un pulsante "Visualizza", colegato allo use case relativo (`VisualizzaBase` o `VisualizzaPremium`).

## Postcondizioni: 
Nessuna.  
## Sequenza degli eventi alternativa: 
`AssenzaContenuti`,  `ErroreCaricamento`

# Caso d'Uso: Login
## Breve Descrizione: 
Permette all'utente di accedere al suo account personale tramite il metodo di accesso definito nella registrazione.
## Attori primari: 
- Utente
## Attori secondari: 
- Google
- Facebook
## Precondizioni: 
L'utente deve essersi registrato.
## Sequenza degli eventi principale:
1. L'utente accede alla sezione "Login" `cliccando un bottone apposito`.
2. Se l'utente ha fatto la registrazione con mail
2.1 deve inserire mail e password nei campi di un form.
3. Altrimenti se l'utente si e registrato con google
3.1 dovra accedere con il suo account google.
4. Altrimenti se l'utente si e registrato con facebook 
4.1 dovra accedere con il suo account facebook.
5. Fintantoche le credenziali non sono corrette
5.1 viene chiesto all'utente di inserirle nuovamente.
6. Il sistema comunica all'utente che ha effettuato correttamente l'accesso.
7. L'utente ha effettuato il login.

## Postcondizioni: 
L'utente ha effettuato il login.
## Sequenza degli eventi alternativa: 
`ErroreCaricamento`
