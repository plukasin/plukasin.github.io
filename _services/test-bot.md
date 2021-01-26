---
title: "IKEA BOT"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Wypróbuj naszego bota. Zobacz jak działa na przykładzie badania NPS sklepu Ikea. Możesz z nim **porozmawiać** i zobaczyć jak rozmowa wygląda dla klienta.

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
    title: "Rozmowa o Ikea",
    subtitle: "Twoje doświadczenia z tym sklepem",
    params: {"storage": "session"} // can be set to "local"  or "session". details in storage section.
  })
</script>

## Przebieg rozmowy

Bot zapyta Cię jak bardzo jesteś gotowy/a polecić sklep na skali od 0 do 10. 
Następnie poprosi o podanie głównych powodów tej oceny. 
Twoja odpowiedź może być wstępem do rozmowy na temat tego co się Tobie podoba lub wymaga ulepszeń.

To jak rozwinie się Wasza rozmowa, a więc również jakie informacje uzyska bot, zależy od Twoich odpowiedzi. Gdzie to możliwe, bot może podać wskazówki jak rozwiązać problem który zgłaszasz.  
    
## To pierwsza wersja 

Twoja rozmowa z botem pomoże nam udoskonalić bota. Zapraszamy ponownie za tydzień. 
Zobaczysz jak dużo się nauczył.





 

