---
title: "IKEA BOT"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Wypróbuj naszego bota. IKEA BOT to testowy bot przygotowany 
do badania NPS dla sklepu IKEA. Możesz z nim **porozmawiać** i zobaczyć jak badanie wygląda dla klienta.

## NPS IKEA BOT 
    
<div id="webchat"></div>
<script src="https://cdn.jsdelivr.net/npm/rasa-webchat/lib/index.min.js"></script>
Na dole ekranu znajdziesz guzik który połączy Cię z naszym testowym botem. 
<script>
  WebChat.default.init({
    selector: "#webchat",
        initPayload: "/przywitaj",
    inputTextFieldHint: "Napisz coś",
    socketUrl: "https://test.qans.pl",
    socketPath: "/socket.io/",
    title: "Ikea Test Bot",
    subtitle: "Uczę się",
    params: {"storage": "session"} // can be set to "local"  or "session". details in storage section.
  })
</script>

## Przebieg rozmowy

Bot zapyta Cię jak bardzo jesteś gotowa polecić sklep na skali od 0 do 10. 
Następnie poprosi o podanie głównych powodów tej oceny. 
Twoja odpowiedź może być wstępem do rozmowy na temat tego co się Tobie w danym produkcie podoba, a co wymaga ulepszeń.

To jak rozwinie się konwersacja, a więc również jakie informacje uzyska bot, zależy od Twoich odpowiedzi. Gdzie to możliwe, system może podać wskazówki jak rozwiązać problem który zgłaszasz. Może są jakieś opcje których nie znałaś, albo inne sposoby na uzyskanie tego czego wydaje się brakować w ofercie. 
Na zakończenie bot zapyta czy może Ty masz jakieś porady dla innych klientów sklepu. 
## To pierwsza wersja 

To pierwsza wersja naszego bota więc jego możliwości dialogu są bardzo ograniczone. 
Twoja rozmowa z botem pomoże nam go udoskonalić. Zapraszamy ponownie za tydzień. 
Zobaczysz jak dużo się nauczył.





 

