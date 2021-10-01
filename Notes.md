-- HANDLEIDING ------------------------------------------------------------
- Huidige directory is /home/kees/Dropbox/MijnLinks
- Maken file in LO Calc.
- Gebruik File > Save as
    - Export naar XHTML geeft een probleem met de Borders
- Vul Properties > Title om een naam te tonen in de tab van de browser
- Kolombreedte wordt door de browser gescaled naar de volledige pagina.

-- HTML file in een bestaande file zetten ---------------------------------------------------
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

-- DONE -------------------------------------------------------------------
- Is het mogelijk om de achtergrond van de niet gevulde cellen aan te passen (Misschien met een beperking op de cellen)
    - Achtergrond kan eventueel aangepast worden door de cellen een kleur te geven en een spatie in 1 van de cellen te zetten.
    - Om de gekleurde cellen blijft een witte rand zichtbaar; NIET DOEN, GEWOON LEEG LATEN
- Borders toevoegen (grijs of de kleur van de cellen)
- Naar Github saven