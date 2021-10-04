-- HANDLEIDING ------------------------------------------------------------
- Huidige directory is /home/kees/Dropbox/Linken
- Maken file in LO Calc.
- Gebruik File > Save as > Kies html
    - Export naar XHTML geeft een probleem met de Borders
- Vul Properties > Title om een naam te tonen in de tab van de browser
- Kolombreedte wordt door de browser gescaled naar de volledige pagina.
- Zorgen dat de bookmark beschikbaar is op alle PC's.
    - Verwijzen naar een file op de PC werkt niet omdat de link naar de folder op Dropbox de naam van de user bevat.
    - Opgelost door de site te hosten vanaf GitHub.
        - Om te hosten moet een index.html en een _config.yml file gemaakt worden.
        - Gebruikte template is minimal.
    - Bookmarks direct naar de files met de linken, dus niet naar de index.

-- HTML file in een bestaande file zetten ------------------------------------------------
Je hebt niet toegang tot alle sites. Bijvoorbeeld O365 weigert contact.
```
<body>
    <iframe src="./Linken_MASTER.html" frameborder="0" scrolling="yes" seamless="seamless"
        style="display:block; width:100%; height:100vh;"></iframe>
</body>
```
N.B. Met _height:100vh_ kan je de hoogte bepalen. 100vh geeft een scrolbalk. 8b vh niet.
Eventueel volgende tekst komt ver eronder te staan als je deheight niet aanpast.

-- TODO -------------------------------------------------------------------
- Navigatie maken in geval van meerdere tabbladen met html (zie code voor iframe in de Handleiding hierboven).

- Beschrijving maken van de handleiding (zie boven)
- Link in de bookmark werkt niet voor Sophia
    - Oorzaak: Link verwijst naar de folder Kees
    - Link via Dropbox: Dropbox ondersteunt het renderen van html files niet meer. Wordt Download of een Dropbox GUI.
    - Via Github: site aangemaakt, maar de template overschrijft de Readme.md
        - 04-10-2021 reste van Git gedaan.

-- DONE -------------------------------------------------------------------
- Is het mogelijk om de achtergrond van de niet gevulde cellen aan te passen (Misschien met een beperking op de cellen)
    - Achtergrond kan eventueel aangepast worden door de cellen een kleur te geven en een spatie in 1 van de cellen te zetten.
    - Om de gekleurde cellen blijft een witte rand zichtbaar; NIET DOEN, GEWOON LEEG LATEN
- Borders toevoegen (grijs of de kleur van de cellen)
- Naar Github saven