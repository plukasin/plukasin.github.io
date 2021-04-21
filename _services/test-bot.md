---
title: "Demo Działania Chatbota NPS"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Chatbot do pomiaru i poprawy NPS 

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

### Przykład badania satysfakcji klientów sklepu Ikea 

- Chatbot prowadzi badanie NPS za pośrednictwem dialogu.
- Analizuje tekst uzasadnienia odpowiedzi i generuje analizę głównych czynników poprawiających i osłabiających NPS.
- W trakcie interakcji proponuje interwencję (poprawia NPS) poprzez usunięcie problemu zgłoszonego przez klienta.

Kod udostępniony jako Open Source na [github.com](https://github.com/QANS-repo/NPS-bot).
 
## Analiza wyników na żywo 

W tym [arkuszu w Google](https://docs.google.com/spreadsheets/d/1z75IvbADrUG6475gyoXVgpmciNvje0NsHi4xcOg17O0/edit?usp=sharing)
 możesz śledzić jak rozmowa na żywo jest analizowana i zamieniana na tematy (aspekty). 
Spróbuj poruszyć temat jak np. tłok, kolejki przy kasach, probelmy z dostawą lub dowolny inny i zobacz jak natychmiast Twoja odpowiedź zostanie zaklasyfikowana do odpowiedniego koszyka.

Poniżej umieszczona jest prosta wizualizacja danych zapisanych w arkuszu. Ten wykres odświeża się co 5 minut.  
<iframe width="699" height="485" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQu73zPf0UhLO0UrY5Oce9RcUHaYnz4kt2ZSXyaC60kFIKupw4KarkOfNIiHRgp4dkkvrdWDzjeNVbs/pubchart?oid=400435005&amp;format=interactive"></iframe>
System jest dostępny jako open source i możesz go bezpłatnie zainstalować w swojej organizacji. Dodatkowe informacje znajdziesz w [dokumentacji](https://github.com/QANS-repo/NPS-bot).
System jest oparty o AI i jego możliwości rosną wraz z liczbą rozmów które przeprowadział.
Więcej infomacji jak wykorzystać chatbota znajdziesz w zakładce [Jak poprawić NPS](https://www.qans.pl/services/) oraz w dokumentacji.

Połączenie z Google Sheet jest dla demonstracji. Przy większych badaniach zalecamy zapisanie tych danych w lokalnej bazie danych i udostępnienie w Excelu/ Tableau etc.  

 








 

