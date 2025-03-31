# Solcellsmonitor
Information om Pi:n som kör programmet for att visa datan från solcellerna

## Tidigare setup: 

Raspberry Pi 3 användes med tidigare ett SDG3-kort (det stora kortet som sitter i USB:n, här finns koden för programmet) och ett MicroSD-kort. 
 
Pi:n startade inte av okänd anledning. Lösning: 
Den ersattes med en ny Raspberry Pi 5. 

## Nuvarande setup: 

Raspberry Pi 5 används med ett SDG3-kort (här finns koden för programmet) och ett MicroSD-kort. 
 
Kod för programmet hittas i: “/media/upptechsolar/root/home/pi/web/public/”. 
 
# Inloggningsuppgifter: 

Användarnamn: upptechsolar 

Lösenord: solcell25 

 
## Problem som uppstod: 

* CORS errors (tomma värden från solcellerna på displayen) 

* Autostart (få programmet att köras direkt vid uppstart) 

* Muspekaren försvinner inte efter uppstart 

* “Your file couldn’t be accessed” (vit skärm med error-meddelande)
