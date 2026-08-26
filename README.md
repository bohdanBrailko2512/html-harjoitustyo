# HTML-harjoitustyö: Keyboard Bot -esittelysivusto

## Mikä on verkkosivustosi aihe?
Sivuston aiheena on itse kehittämäni Telegram-botti ("Keyboard Bot"), joka on tarkoitettu vieraiden kielten sanaston harjoittelemiseen.

## Mitä uutta opit tehtävää tehdessäsi?
Opin rakentamaan loogisen ja monisivuisen verkkosivuston pelkällä HTML:llä. Opin myös käyttämään suhteellisia tiedostopolkuja (kuten `../kuvat/`) sekä linkittämään sivuja toisiinsa oikein.

## Mikä oli vaikein kohta?
Vaikeinta oli aluksi ymmärtää kansiorakenne ja se, miten suhteelliset polut toimivat eri kansioissa olevien tiedostojen välillä, sekä GitHubin versiohallinnan konfliktien ratkaiseminen.

## Minkä HTML-elementin käyttö oli sinulle uusi asia?
Erityisesti kuvauslistan (`<dl>`, `<dt>`, `<dd>`) sekä lomakkeen ryhmittelyelementtien (`<fieldset>`, `<legend>`) käyttö olivat minulle uusia ja hyödyllisiä asioita.

## Mitä semanttisia HTML-elementtejä käytit?
Käytin laajasti HTML5:n semanttisia elementtejä, kuten `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<figure>` ja `<figcaption>`.

## Miksi käytit juuri näitä elementtejä? (Kolme perustelua)
1. **`<nav>`**: Käytin tätä elementtiä sivuston päävalikossa, koska se kertoo selaimelle ja ruudunlukijoille selkeästi, että kyseessä on sivuston tärkein navigointialue.
2. **`<main>`**: Suljin sivun varsinaisen sisällön main-elementtiin, jotta se erottuu selkeästi toistuvista osista kuten ylätunnisteesta ja alatunnisteesta.
3. **`<aside>`**: Käytin aside-elementtiä "Toiminnallisuus"-sivulla oppimisvinkin esittämiseen, koska kyseessä on pääsisältöön liittyvä, mutta siitä erillinen lisätieto.

## Mitä HTML-validaattori löysi? Millaisia HTML-virheitä korjasit?
Validaattori auttoi löytämään muutamia puuttuvia sulkeita ja varmistamaan, että kaikki tunnisteet (kuten lomakkeiden labelit) oli yhdistetty oikein input-kenttiin. Korjasin nämä, ja nyt tavoitteena on 0 virhettä.

## Mitä teit sivuston saavutettavuuden parantamiseksi?
Määritin dokumentin kieleksi suomen (`<html lang="fi">`), lisäsin kuville kuvaavat `alt`-tekstit, huolehdin loogisesta otsikkohierarkiasta (h1, h2, h3) ja yhdistin lomakekentät selkeästi `<label>`-elementteihin `for`- ja `id`-attribuuttien avulla.

## Mitä tekisit sivustolle seuraavaksi, jos saisit käyttää CSS:ää?
Lisäisin sivustolle visuaalista ilmettä: muuttaisin fontteja, asettelisin elementtejä vierekkäin, lisäisin värejä ja tekisin sivustosta responsiivisen eri ruutukooille.