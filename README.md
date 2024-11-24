# Tamagotchi Vue Projekt

Tamagotchi-spel byggt med Vue 3 och Composition API. Spelet simulerar ett virtuellt husdjur som du kan mata, leka med och återställa. Husdjurets humör ändras baserat på dess hunger- och lyckonivåer.

## Komma igång

### Förutsättningar

- Node.js (version 12 eller högre)
- npm (version 6 eller högre) eller yarn

### Installation

1. Klona repot:
   ```sh
   git clone <repository-url>
   ```

2. Navigera till projektkatalogen:
   ```sh
   cd tamagotchi
   ```

3. Installera beroenden:
   ```sh
   npm install
   # eller
   yarn install
   ```

### Köra projektet

För att starta utvecklingsservern, kör:
```sh
npm run dev
# eller
yarn serve
```

Öppna din webbläsare och navigera till `http://localhost:5137` för att se applikationen.

## Uppgifter

### Saknade funktioner & variabler

1. **Definiera `TamagotchiState`-gränssnittet**:
   - Se till att gränssnittet inkluderar egenskaperna `hunger`, `happiness` och `mood`.

2. **Initiera `tamagotchiState`**:
   - Initiera `tamagotchiState`-objektet korrekt med standardvärden för `hunger`, `happiness` och `mood`.

3. **Implementera `feed`-metoden**:
   - Minska `hunger`-nivån med en viss mängd.
   - Se till att `hunger`-nivån inte går under 0.

4. **Implementera `play`-metoden**:
   - Öka `happiness`-nivån med en viss mängd.
   - Se till att `happiness`-nivån inte överstiger 100.

5. **Implementera `reset`-metoden**:
   - Återställ `hunger`, `happiness` och `mood` till deras standardvärden.

6. **Uppdatera template**:
   - Visa `name`, `hunger`, `happiness` och `mood` i mallen.
   - Lägg till knappar för att utlösa `feed`, `play` och `reset`-metoderna.

## Bidra

Om du vill bidra till detta projekt, vänligen fork repot och skapa en pull request med dina ändringar.

## Licens

Detta projekt är licensierat under MIT-licensen. Se LICENSE filen för detaljer.

---

Känn dig fri att lägga till fler uppgifter eller ändra de befintliga efter behov. Denna lista bör hjälpa till att vägleda utvecklingsprocessen och säkerställa att alla nödvändiga funktioner och variabler implementeras.