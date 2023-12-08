# moment2backend

# Sport API

Jag har gjort ett api för sporter, en webbtjänst som ger information om olika sporter. Nedan finns en översikt av de tillgängliga CRUD-endpoints.

## Endpoints

### Hämta alla sporter

GET /api/sports

Returnerar en lista över alla sporter.

### Hämta en specifik sport

GET /api/sports/{id}

Returnerar information om en specifik sport baserat på dess id.

### Lägg till en ny sport

POST /api/sports

Skicka en POST-förfrågan med följande JSON-data för att lägga till en ny sport:

{
  "sport_type": "Fotboll",
  "description": "En bollsport som spelas mellan två lag.",
  "medals_count": 4,
  "latest_gold_year": 2018,
}

### Uppdatera en sport

PUT /api/sports/{id}

Skicka en PUT-förfrågan med uppdaterad JSON-data för att ändra information om en befintlig sport.

### Radera en sport

DELETE /api/sports/{id}

Skicka en DELETE-förfrågan för att ta bort en specifik sport.


## Övrigt

- Laravel (version 10.32.1)
- PHP (version 8.2.12)
- MySQL
