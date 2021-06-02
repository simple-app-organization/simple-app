# Sviluppare una simple-app

L'idea è rendere possibile creare un'applicazione semplice, ma funzionante.  
Non sarà un'applicazione che serve per andare sulla luna, ma può iniziare a darti le basi per avviare il tuo business o per realizzare l'applicazione per andare sulla luna :)  

## UML Diagrams  

### Casi d'uso

#### Creare una simple-app
![Diagram](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-create-UseCaseDiagram.svg)  
[drawio](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-create-UseCaseDiagram.drawio)  
[svg](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-create-UseCaseDiagram.svg)  

#### Editare il contenuto (e la simple-app)
![Diagram](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-edit-UseCaseDiagram.svg)  
[drawio](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-edit-UseCaseDiagram.drawio)  
[svg](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-edit-UseCaseDiagram.svg)  

#### Usare la simple-app
![Diagram](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-use-UseCaseDiagram.svg)  
[drawio](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-use-UseCaseDiagram.drawio)  
[svg](https://github.com/simple-app-organization/simple-app/blob/main/Project/Diagrams/simple-app-use-UseCaseDiagram.svg)  

## Linee guida

Una *simple-app* deve avere:

- dei dati in plain text (json, markdown o altro formato semplice) che l'utente potrà modificare (nella sezione [File di esempio](#file-di-esempio) trovare una base di partenza)
- dei test per verificare il funzionamento dei componenti e delle funzionalità

Una *simple-app* **non** deve avere:

- un database o delle webapi da richiamare

## File di esempio

Nella cartella */data* sono presente una serie di file *json* e *markdown* di esempio da utilizzare per realizzare la tua _simple-app_.  
- home_messages.json - una serie di messaggi da visualizzare in home page
- people.json - una lista di persone
- places.json - una lista di luoghi
- pages/*.md - sono presenti i contenuti delle pagine da visualizzare

Questi file devono rimanere semplici da modificare perché saranno quelli che l'utente (o il webmaster/webdesigner) userà per aggiornare il proprio sito.

