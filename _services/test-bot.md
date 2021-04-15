---
title: "Demo Działania Chatbota NPS"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Badanie Satysfakcji Klientów Sklepu Ikea

<div id="webchat"></div>
<script src="https://cdn.jsdelivr.net/npm/rasa-webchat@0.11.11/lib/index.min.js"></script>

<script>
  window.onload = WebChat.open;
  WebChat.default.init({
    selector: "#webchat",
    initPayload: "/przywitaj",
    inputTextFieldHint: "Napisz coś",
    socketUrl: "https://test.qans.pl",
    socketPath: "/socket.io/",
    title: "Demo badania NPS",
    subtitle: "Twoje doświadczenia z IKEA",
    params: {"storage": "session"} // can be set to "local"  or "session". details in storage section.
  })
  
</script>

## Przebieg rozmowy

Bot zapyta Cię jak bardzo jesteś skłonny/a polecić sklep na skali od 0 do 10. 
Następnie poprosi o podanie głównych powodów tej oceny. 
Twoja odpowiedź jest wstępem do rozmowy na temat tego co się Tobie podoba, a co wymaga ulepszeń.

W miarę swoich możliwości, bot będzie się starał podać Ci rozwiązania problemów, które zgłaszasz.  
    
## Analiza wyników na żywo 

W tym [arkuszu w Google](https://docs.google.com/spreadsheets/d/1z75IvbADrUG6475gyoXVgpmciNvje0NsHi4xcOg17O0/edit?usp=sharing)
 możesz śledzić jak rozmowa na żywo jest analizowana i zamieniana na tematy (aspekty). 
Spróbuj poruszyć jeden z tematów (np. kolejek przy kasach, dostwy lub inny) i zobacz jak natychmiast Twoja odpowiedź zostanie zaklasyfikowana do odpowiedniego koszyka.

Poniżej umieszczona jest prosta wizualizacja danych zapisanych w arkuszu. Ten wykres odświeża się co 5 minut.  
<iframe width="600" height="493" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQu73zPf0UhLO0UrY5Oce9RcUHaYnz4kt2ZSXyaC60kFIKupw4KarkOfNIiHRgp4dkkvrdWDzjeNVbs/pubchart?oid=1224597091&amp;format=interactive"></iframe> 

Dodatkowe informacje znajdziesz w [dokumentacji](https://github.com/QANS-repo/NPS-bot).
System jest oparty o AI i jego możliwości rosną wraz z liczbą rozmów które przeprowadział.

Połączenie z Google Sheet jest dla demonstracji. Przy większych badaniach zalecamy zapisanie tych danych lokalnie.  







 

