---
title: "Ikea BOT"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Wypróbuj naszego bota. [Ikea Bot](#Ikea) to nasz testowy bot przygotowany 
do badania NPS dla sklepu IKEA. Możesz z nim **porozmawiać** i zobaczyć jak badanie wygląca dla kienta.


## NPS Ikea Bot 
    
<div id="webchat"></div>
<script src="https://cdn.jsdelivr.net/npm/rasa-webchat/lib/index.min.js"></script>
Na dole ekranu znajdzieś guzik który połączy Cię z naszym testowym botem. 
<script>
  WebChat.default.init({
    selector: "#webchat",
    initPayload: "/get_started",
    socketUrl: "http://54.216.52.37",
    socketPath: "/socket.io/",
    title: "Ikea Test Bot",
    subtitle: "Uczę się",
    params: {"storage": "session"} // can be set to "local"  or "session". details in storage section.
  })
</script>
## Jak przebiega  rozmowa

Bot zapyta Cię jak bardzo jesteś gotowa polecić sklep na skali od 0 do 10. 
Następnie poprosi o podanie głównych powodów tej oceny. 
Twoja odpowiedź może być wstępem do rozmowy na temat tego co się Tobie w danym produkcie podoba a co wymaga ulepszeń.

To jak rozwinie się konwersacja, a więc również jakie infromacje uzyska bot, zależy od Twoich odpowiedzi. 
Gdzie to możliwe może podać wskazówki jak rozwiązać problem jaki zgłaszasz. Może są jakieś opcje których nie znałaś, 
albo inne sposoby na uzyskanie tego czego wydaje się brakować w ofercie. 

## To piersza wersja 

To piersza wersja naszego bota więc jego moźliwości dialogu są bardzo ograniczone. 
Twoja rozmowa z botem pomoże nam go udoskonaić. Zapraszamy ponownie za tydzień. 
Zobacz jak dużo się nauczył.

 

