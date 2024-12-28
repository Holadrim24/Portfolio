Portfolio-projekt, Vinter 2024

1. Header
 -- Headern består utav en background-image som är satt till att stretcha ut sig över hela bredden av sidan
2. Navbar
 -- Navbaren är en flexbox row som är centrerad och har padding mellan de olika ikonerna
 -- Position är satt till sticky så att navbaren följer med högst upp på skärmen när man scrollar ned
 -- Varje ikon är en länk till en div precis ovanför de stora ikonerna (ovanför headers) för varje section i Main (inkluderat padding för att skärmen inte ska placera sig i mitten av ikonen efter scroll)
 -- När man har muspekaren över varje ikon så ändrar den färg (via pseudo-klassen :hover) och om man håller den där ett litet tag så visas en beskrivande text (title) som en tooltip
3. Main
 -- Main är uppdelad i många sections för att underlätta lokalisering av olika element. Där det finns behov av paragrafer så används article inom dessa sections.
 -- Det finns en knapp/ikon för att ladda ned en pdf-fil med ett CV precis under profilbilden
 -- Alla ikonerna i main har liknande beteende som de i navbaren, dvs de ändrar färg och har en tooltip
4. Footer
 -- Footer är en simpel background-image som bestämts i CSS-filen. Copyright-texten är satt att vara till höger i normalläge (över 600 pixlar) och i mitten i mobilläge
5. Responsivitet
 -- Sidan funkar även i mobilläge och headers och paragrafer ändrar storlek för att se okej ut i det formatet
