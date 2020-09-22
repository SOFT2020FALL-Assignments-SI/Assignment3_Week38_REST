## Assignment3_Week38_REST
**[Assignment Link](https://datsoftlyngby.github.io/soft2020fall/resources/fbbdae82-A3-REST-Read.pdf)**  
  
**[Source Link](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)**  

### REST
**What exactly is REST? How does the context of it fits to the title of the dissertation?**:  
REST er en standard for kommunikation mellem systemet på Internettet. REST er stateless, hvilket betyder at serveren og klienten ikke behøver kende hinandens state, når der forespørges på en ressource på en server. Klienten holder selv state, og er ansvarlig for at give serveren alle nødvendige oplysninger ved et request, og serveren kan ikke gøre brug af tidligere requests.  

**Why is the dissertation considered so important for the software-architectural
world?**  
Det er vigtigt på grund af den måde, hvorpå man tilgår en ressource, f.eks. ved hjælp af GET, PUT, POST, DELETE. Det gør det meget nemmere i forhold til andre ”client-server” arkitekturer, da man her konkret i hvert request kan angive sin type af request.  

**Which is the most valuable outcome you personally get from it?**  
Det er vigtigt, at man i headeren specifikt kan fortælle hvilken format/type man acceptere på klienten, f.eks. at man skal bruge JSON, og dermed i headeren kan sige accept application/json.
Dette er med til at man kan forvente at få responset i et bestemt format/type, og derfor kan arbejde ud fra det på sin egen kodebase.
  

**How could you implement it in your own practice as a software developer?**  
Hvis du har data som skal være tilgængeligt fra andre, som skal kunne forespørge på det, kan du som udvikler oprette RESTendpoints, hvor man kan lave response med data i det format, som er ønsket f.eks. JSON, så andre systemer kan forespørge på en bestemt URI, og modtage data retur i et response.
***  
   

