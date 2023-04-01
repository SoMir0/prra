---
title: "Tabele, Css"
date: 2023-03-31
draft: false
---
Na današnjem času nastavili smo sa osnovama HTML-a, i počeli smo učiti CSS.

# Tabele

Tabela u HTML se definiše tagovima `<table></table>`

Red se definiše sa `<tr>`, a ćelija sa `<td>`.

Tabeli se takođe može dodati naslov sa `<caption>`, a naslov u ćeliji `<th>`.

# CSS

Cascading Style Sheets, poznatiji kao CSS, je jezik sa dizajniranje izgleda website-a. Da bi se pisao CSS kod, mora postojati HTML osnova.

Sintaksa je sledeća:

`
ime-selektora {
    atribut 1: vrednost;
    atribut 2: vrednost;
    ...
}
`

Za ime selektora se može koristiti bilo koje ime taga u HTML, kao i klase i ID-ovi.

Klasa ili id se u HTML dodaje na sledeći način:

`<element class="ime-klase" id="id-elementa">`

U CSS-u možemo selektovati ovaj element na 3 načina:

`
element {          <-- selektovanje preko imena taga
...
}

.ime-klase {       <-- selektovanje preko klase
...
}

#id-elementa {     <-- selektovanje preko id-a
...
}
`

U CSS-u postoje razni atributi, koji mogu menjati veličinu, boju, font, boju pozadine, poziciju, animaciju, i još mnogi.

Ovo je primer CSS-a koji boji dugme u crveno (pozadinu) i tekst u žuto:

`
button {
    color: yellow;
    background-color: red;
}
`
![dugme](https://i.imgur.com/mJdRUtq.png)
