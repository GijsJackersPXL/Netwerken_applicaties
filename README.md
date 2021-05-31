# Netwerken_applicaties

Je maakt een 4 applicaties (UDP Client, UDP Server, TCP Client en TCP Server) die via Berkley sockets in C met elkaar over internet kunnen communiceren. De 2 Server applicaties draaien op je PYNQ en de 2 Client applicaties draaien op je laptop.

# Welke onderdelen zijn behaald van de UDP Client & Server ?
- Werkende Client applicatie die aantal terug te sturen packetten via UDP stuurt en deze packetten via UDP ontvangt [2/10]
- Werkende Server applicatie die na het ontvangen van een "aantal" via UDP, dat aangevraagd aantal packetten via UDP terugstuurt [2/10]
- Clean en performante code [1/10]
- Er is zekerheid van aflevering (Client->Server) toegevoegd EN de server moet nooit herstarten voor alles juist te laten werken [2/10]
- Er worden op de Client een statistiek van aantal succesvol ontvangen pakketten uitgeprint worden [2/10]
- Een extra dat netwerk programmeren gerelateerd is [1/10]

# Welke onderdelen zijn behaald van de TCP Client & Server ?
- Werkende Client applicatie die door de gebruiker ingegeven berichten doorstuurt via TCP [2/10]
- Werkende Server applicatie die na het ontvangen van een bericht dit naar alle deelnemers stuurt met de afzender (e.g. IP-adres van zender) [2/10]
- Clean en performante code [1/10]
- Er kunnen meerdere Clients simultaan verbonden zijn en chatten met elkaar (i.e. assynchroon of synchroon verwerkt op de server) [2/10]
- Er kan tegelijk berichten gestuurd en ontvangen worden op de Client zonder afgesproken beurtrol (e.g. multi-threaded) [2/10]
- Een extra dat netwerk programmeren gerelateerd is [1/10]
