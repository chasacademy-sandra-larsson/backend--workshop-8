
# Backendutveckling och API:er #8: GraphQL 
👋 Se Linus Rudbecks föreläsning från 29 maj ✅ 

**Syftet med denna workshop:** Grunderna i hur man bygger ett GraphQL API samt hur man gör förfrågningar i GraphQL. 


### Innan du börjar övningen:

Vara klar med workshop 7 där du CRUD:ar utifrån 2 (eller 3) tabeller i MySQL (eller annan SQL-form). **I denna workshop ska du utgå från samma kodbas och använda GraphQL** istället för REST.

**Tips!** Istället för MySQL Workbench, ta en titt på [DBGate](https://dbgate.org/). Finns för både Windows/Mac och Linux och har stöd för flera databaser, vilket kan vara bra till senare projekt.

**Ha koll på 🤓**

* Vad är skillnaden mellan GraphQL och REST?
* Vad gör GraphQL bättre än REST?
* När finns det anledning till att använda REST framför GraphQL

* Beskriv de olika beståndsdelarna i GraphQL - schema, typer, query och mutation
* Vad är en resolver-funktion?
* Hur många endpoints har GraphQL?
 
**Testa 💻**

* [Testkör Starwars i GraphiQL](https://graphql.github.io/swapi-graphql/?) för att lära dig hur man kör queries och mutations
* [Hello World i GraphQL](https://graphql.org/graphql-js/running-an-express-graphql-server/) - Installera npm-paket och få det att snurra.
Obs! Man kan bygga vidare på detta exempel, men Linus använder en liten annan metod där schema och resolvers ligger mer ihop (enklare att hålla koll på typerna). Jämför ex med [denna](https://github.com/linus-rudbeck/graphql-blog/blob/main/server-demo-1.js) 



# 👩🏽‍💻 Övning: Skapa ett GraphQL API på workshop 8

**Din uppgift:**
Du ska bygga vidare på workshop 8 där du har skapat CRUD för 2-3 tabeller i MySQL (eller annan SQL-form). Istället för att din data exponeras genom REST ska den exponerar genom ett GraphQL API. 

Börja med att studera exempel och förstå skillnaden mellan schema, types, mutation osv. 
Tänk på att mutation endast innehåller förändrade data d.v.s här ligger Create, Update, Delete = CUD (🐟, torska inte denna). Read blir ju fälten (fields) som man definerar. 

Nytt sätt att tänka! Fråga om du kör fast!


### Redovisning:
* Du redovisar fungerande GraphQL API där man kan göra queries och mutations i GraphiQL på de resurser du har specifierat i tabellerna.
* 
***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***
