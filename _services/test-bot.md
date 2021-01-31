---
title: "Bot dla Klientów sklepu Ikea"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

Porozmawiaj z naszym botem o Twoich doświadczeniach ze sklepem Ikea.

<div id="webchat"></div>
<script src="https://cdn.jsdelivr.net/npm/rasa-webchat/lib/index.min.js"></script>

<script>
  WebChat.default.init({
    selector: "#webchat",
    initPayload: "/przywitaj",
    inputTextFieldHint: "Napisz coś",
    socketUrl: "https://test.qans.pl",
    socketPath: "/socket.io/",
    title: "Rozmowa o Ikea",
    subtitle: "Twoje doświadczenia z tym sklepem",
    embedded: "true",
    params: {"storage": "session"} // can be set to "local"  or "session". details in storage section.
  })
</script>

## Przebieg rozmowy

Bot zapyta Cię jak bardzo jesteś skłonny/a polecić sklep na skali od 0 do 10. 
Następnie poprosi o podanie głównych powodów tej oceny. 
Twoja odpowiedź jest wstępem do rozmowy na temat tego co Ci się podoba, a co wymaga ulepszeń.

W miarę swoich możliwości, bot będzie się starał podać Ci rozwiązania problemów, które zgłaszasz.  
    
## Nieustannie udoskonalamy bota

Twoja rozmowa z botem pomoże nam go nauczyć nowych zwrotów i tematów.
Dziękujemy za pomoc!





 

