# BIBLIOTEKSTEST
Detta är ett embryo till backend och API för att skapa och hantera ett bibliotek. 

## Inför uppgiften
Uppgiften kräver att du har basförståelse av Spring Boot och Spring Data JPA. Om du inte känner till dessa, googla lite på nätet, där förklaras dessa bra.

## UPPGIFT
Vi vill att du implementerar någon/några av de användningsfall som finns listade nedan.

Det vi vill uppnå med uppgiften är att se kodstil, kodkvalitet och struktur, samt att ha kod att prata om på den tekniska intervjun.

Du bör inte lägga mer än 3-5 timmar på uppgiften. Om du inte fått någon annan information av oss ber vi att du epostar oss din lösning
minst tre arbetsdagar innan intervjun.

### Användarfall:
* Som kund vill jag kunna söka efter böcker med titel eller författare.
* Som kund vill jag sortera mina sökresultat efter titel eller författarnamn.
* Som kund vill jag få ett informativt felmeddelande då jag skickat fel data till tjänsten.
* Som admin vill jag kunna göra alla CRUD-operationer på "book".
* Introducera "book genre" och möjliggör att söka och sortera med hjälp av det.
* Som admin vill jag kunna göra alla CRUD på "kund". Det betyder att du ska skapa en "customer" klass.
* Som kund vill jag kunna låna och återlämna böcker.
    * En kund kan inte boka fler än 2 böcker.
* Som kund vill jag kunna få lista på alla böcker som man har lånat.
* Som adm vill man kunna köra alla CRUD operationer på "author". "Author" ska ha "name", "nationality", "List of books".

### Att tänka på
* Avsikten är INTE att du ska implementera alla dessa användningsfall, utan välj någon/några av dem.
* Du bestämmer själv hur du vill verifiera och dema funktionaliteten.
* Använd tredjeparts-libs om du vill.

### Tips
1. När du startat applikationen kan du i valfri browser gå till http://localhost:8080/swagger-ui/ för att se
dokumentationen av API:et, där kan du också testa att göra requester.

2. In-memory databasen (H2) når du genom att öppna `http://localhost:8080/h2-console` i din browser. 
   Användarnamn är "sa", lösenord och URL till databasen finns i [application.properties](src/main/resources/application.properties)


## Lycka Till!"# Library" 
