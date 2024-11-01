## Testo prova scritta
Il repository corrente contiene i seguenti file:

* home.html
* courses.html
* contact.html
* tpsi_5a_24_25.html
* style.css

E' già presente del codice di partenza in ciascuno dei file elencati sopra.
Il tuo compito è quello di aggiungere il codice mancante e completare il sito.
Di seguito sono elencati i punti per il completamento del sito:

1. In tutte le pagine, all'interno di `<head>` sotto `<title>` linka il file css esterno: `style.css`
2. Appena sotto il `<body>`, aggiungi un `div` contenente una lista non ordinata: tag `<ul>`
   * Inserisci tre list items per le pagine: `home.html`, `courses.html`, `contacts.html` ed aggiungi rispettivamente i seguenti testi: `Home`, `Courses`, `Contacts`
   * Rendi cliccabili i tre list items in modo da reindirizzare l'utente alla pagina corretta
3. Assegna al `div` creato al punto 2. la classe `header` ed al tag `ul` la classe `nav`

![punti_1_2_3](https://github.com/user-attachments/assets/6eb50cfd-5990-43c3-8b88-f7172ca083e9)

4. Allinea al centro il testo per la classe `nav`

![punto_4](https://github.com/user-attachments/assets/0210f162-6f34-42f6-84c1-69502734db52)

5. Per tutti i list items della classe `nav` imposta:
   * `font-size` a 20 px
   * `font-weight` a bold
   * margine sinistro e destro a 40 px
   * trasforma il list item da block level tag ad inline (in moda da essere mostrati tutti sulla stessa riga)

![punto_5](https://github.com/user-attachments/assets/a953b727-4696-4d18-bec3-a0f6f166b202)

6. Eliminare la riga (sottolineatura) per ogni tag `<a>` della classe `nav`
![punto_6](https://github.com/user-attachments/assets/d98eba33-38c9-4b1a-a6a4-b61fa732dd8b)

7. Applicare alla classe `nav` le seguenti regole
   * colore di sfondo: `#FFD700`
   * padding superiore ed inferiore: 2px
   * bordo: 1 px
   * colore del bordo: `#e7e7e7`

![punto_7](https://github.com/user-attachments/assets/f54e1c7d-2e75-4dc6-bd9c-12f8bee85cb8)

8. Applicare a tutti i tag `<a>` della classe `nav` un colore del testo nero

![punto_8](https://github.com/user-attachments/assets/212d9782-fa5b-4294-bc1f-e9dfeac32a6e)

9. Assegnare in tutte le pagine (`home.html`, `courses.html`, `contacts.html`, `tpsi_5a_24_25.html`) al `div` subito sotto il `div` di chiusura della classe `.header` la classe `main`

10. Settare per la classe `main` le seguenti regole (allineamento al centro della pagina per il `div` .main)
    * larghezza e lunghezza: 900px
    * margine alto e basso: 0
    * margine destro e sinistro: auto
      
![punto_10](https://github.com/user-attachments/assets/dd7e92c1-7274-4181-ace3-b7adad6d984c)

11. Assegna all'ultimo `div` in `home.html` la classe `footer` e copia questo `div` in tutte le altre pagine restanti (sempre come ultimo tag prima della chiusura del `body`)
12. Imposta una larghezza per i tag `img` della classe `footer` pari a 50 px

![punto_12](https://github.com/user-attachments/assets/b34a1d0e-2fbd-4564-ac69-961108ab637c)

13. Trasforma i tag `li` della classe `footer` in inline tag in modo da mostrali sulla stessa riga

![punto_13](https://github.com/user-attachments/assets/d0bca26c-ed00-471d-9b9b-247de923c029)

14. Applica queste regole css alla classe footer per posizinare il footer in basso alla pagina, settare il colore e centrare i tag inline al suo interno

```css
{
    background-color: #FFD700;
    position:absolute;
    bottom:0;
    left:0;
    width:100%;
    text-align: center;
}
```

![punto_14](https://github.com/user-attachments/assets/d367d436-a3c8-474d-8d7c-83b8f4de5776)

15. Assegna in `home.html` al primo `div` dentro la classe `main` (il `div` che contiene `<h2>About me</h2>`) la classe `me`, al `div` successivo (il `div` che contiene `<h2>Working Experience</h2>` la classe `cv`)
  
16. Rendi i tag `img` della classe `cv` flottanti a sinistra ed imposta la loro larghezza e altezza a 60px, aggiungi anche un padding destro di 10px
![punto_16](https://github.com/user-attachments/assets/71f906a8-c3ff-46b3-8cfd-93466d8f5b04)

17. Setta il padding sinistro dei tag `ul` della classe `cv` a zero mentre per i tag `li` della classe `cv`: elimina i pallini, giustifica il testo al loro interno ed infine aggiunti un bordo solo inferiore con linea spessa 1 px e colore `#FFD700`
![punto_17](https://github.com/user-attachments/assets/d4ddabe3-1fdc-4136-bb09-dbbf98ffa1c5)

18. Giustifica il testo della classe `me`, aggiungi l'immagine `images/me.jfif` in `home.html` sotto `<h2>About me</h2>` rendila flottante a sinistra ed imposta un padding destro di 10px

![punto_18](https://github.com/user-attachments/assets/b77001ee-42ca-4249-bb1a-bfa9aad61857)

19. In `courses.html` assegna la classe `courses` al tag `ul` e associa un collegamento ipertestuale al testo `TPSI 5` che porti l'utente (cliccandoci) alla pagina `tpsi_5a_24_24.html`

20. Rendi flottanti a sinistra tutti i tag `img` della classe `courses`, imposta anche per questi tag una larghezza di 170px ed un'altezza di 210px. Infine imposta il padding destro e inferiore a 10px

![punto_20](https://github.com/user-attachments/assets/71f323f5-be80-47cc-9cba-9815d5c18bdc)

21. Elimina il pallino per tutti i tag `li` della classe `courses` ed imposta per loro una larghezza di 900px ed un altezza di 210px

![punto_21](https://github.com/user-attachments/assets/9159338e-10bb-4df7-ae92-9136e1b56ee2)

22.
