---
title: "Demo chatbota NPS"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 3
---

<!-- Messenger Wtyczka czatu Code -->
<div id="fb-root"></div>
<script>
        window.fbAsyncInit = function() {
          FB.init({
            xfbml            : true,
            version          : 'v10.0'
          });
        };
        (function(d, s, id) {
          var js, fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) return;
          js = d.createElement(s); js.id = id;
          js.src = 'https://connect.facebook.net/pl_PL/sdk/xfbml.customerchat.js';
          fjs.parentNode.insertBefore(js, fjs);
        }(document, 'script', 'facebook-jssdk'));
</script>

<!-- Your Wtyczka czatu code -->
<div class="fb-customerchat"
    attribution="biz_inbox"
    page_id="101959758349198">
</div>
      

Przykład badania satysfakcji klientów sklepu Ikea   

- W oknie chatbota odpowiedz na pytanie o ocenę i uzasadnienie.
- System analizuje odpowiedzi i generuje analizę głównych czynników poprawiających i osłabiających NPS.
- W trakcie interakcji chatbot proponuje interwencję (poprawia NPS) proponując rozwiązania.  
 
## Analiza wyników na żywo  

W tym [arkuszu w Google](https://docs.google.com/spreadsheets/d/1z75IvbADrUG6475gyoXVgpmciNvje0NsHi4xcOg17O0/edit?usp=sharing)
 możesz śledzić jak rozmowa jest analizowana i zamieniana na tematy (aspekty). 
Spróbuj poruszyć temat jak np. tłok, kolejki przy kasach, probelmy z dostawą lub dowolny inny. Zobaczysz jak Twoja odpowiedź zostanie zaklasyfikowana do odpowiedniego koszyka.

Poniżej umieszczona jest prosta wizualizacja danych zapisanych w arkuszu. Ten wykres odświeża się co 5 minut.  
<iframe width="699" height="485" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQu73zPf0UhLO0UrY5Oce9RcUHaYnz4kt2ZSXyaC60kFIKupw4KarkOfNIiHRgp4dkkvrdWDzjeNVbs/pubchart?oid=400435005&amp;format=interactive"></iframe>  

Program jest dostępny jako open source na [github.com](https://github.com/QANS-repo/NPS-bot) i możesz go dowolnie używać i modyfikować.  

Jakość klasyfikacji rośnie wraz z liczbą przeprowadzonych rozmów, po naniesieniu poprawek i przetrenowaniu modelu.
Więcej infomacji jak wykorzystać chatbota znajdziesz w zakładce [jak poprawić NPS](https://www.qans.pl/services/) oraz w [dokumentacji](https://github.com/QANS-repo/NPS-bot).  

Połączenie z Google Sheet jest dla demonstracji. Przy większych badaniach zalecamy zapisanie tych danych w lokalnej bazie danych i udostępnienie w Excelu/ Tableau etc.  

 








 

