DS3103 - Web Developmen (CRUD Project)
-
Dette prosjektet ble utviklet som en del av eksamen i faget DSR3103 - Web Development ved Høyskolen Kristiania - høst 2023.

Målet med prosjektet var å utvikle en fullstendig CRUD-applikasjon med egen Web API og database. Frontend kommuniserer med API-et gjennom HTTP-requests (GET, POST, PUT, DELETE)
<hr style="height": 3px>

Teknologier
-
  - Frontend: React, Bootstrap
  - Backend: .NET (C#) Web API
  - Database: SQLite
  - REST API

<hr style="height": 3px>

Funksjonalitet
- 
API-et tilbyr CRUD-operasjoner på ulike ressurser i databasen.

Web API-metoder:

- Hente alle elementer
- Hente elementer etter ID
- Hente elementer etter annen property
- Legg til nye elementer (inkludert bildeopplasting)
- Oppdater eksisterende elementer
- Slett elementer

Frontend bruker disse metodene for å hente og manipulere data fra backend.

<hr style="height": 3px>

Hvordan kjøre prosjektet
-
1. Åpne terminal og naviger til API-mappen:
   cd RacingAPI
   dotnet run
   
3. Start frontend

Åpne terminal og naviger til Frontend-mappen:
cd racing-frontend
npm install
npm start

<hr style="height": 3px>

Om prosjektet
-
Prosjektet viser hvordan man kan bygge en enkel shopping-app i Android med moderne teknologi som Jetpack Compose.

Appen integrerer med et REST API for å hente produktet og gir brukeren mulighet til å se på produkter, legge de til i en handekurv og gjennomføre et "kjøp".

> Resultatet av eksamen ble A
