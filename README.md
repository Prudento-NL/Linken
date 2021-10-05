# Linken
Pagina met hyperlinks zodat je niet afhankelijk bent van de browser bookmarks/favorites en het besturingssysteem.

# Inleiding
De linken pagina is gemaakt m.b.v. Libreoffice Calc in het ods formaat.  
Dit bestand wordt gesaved as html formaat.  
_N.B. Export van de file naar html geeft niet het gewenste resultaat._   
De documenten worden gesynct met een GitHub repo. De linkenpagina's worden gehost vanaf GitHub.  

- Huidige directory: /home/kees/Dropbox/Linken
- GitHub repo: https://github.com/Prudento-NL/Linken
- Linken: https://prudento-nl.github.io/Linken/Published/Linken.html
- K-Linken: https://prudento-nl.github.io/Linken/Published/K-Linken.html

# Github
Voor het hosten vanaf GitHub is een index file gemaakt. Dit is een placeholder en wordt verder niet gebruikt.  
Tevens is een minimale _config.yml gemaakt/aangepast.  
De gebruikte template voor het hosten is jekyll-theme-minimal

- Index: https://prudento-nl.github.io/Linken/index.html

# Aanpassen file
- Open het bestand vanuit de directory: /home/kees/Dropbox/Linken/Source files Libreoffice
- Hernoem het bestand naar de huidige datum
- Verplaats het oude bestand naar /home/kees/Dropbox/Linken/Source files Libreoffice/Old versions
- Pas het bestand aan en save het in de directory ./Source files Libreoffice
- Save het bestand als html in de folder /home/kees/Dropbox/Linken/Published
    - File > Save as > Kies HTML Document (Calc)(.html)
- Gebruik VSCode om het bestand naar GitHub te pushen.

# Nieuwe pagina aanmaken
- Gebruik de file _Template Linken.ods_
- Vul Properties > Title om een naam te tonen in de tab van de browser
- Gebruik File > Save as > Kies HTML Document (Calc)(.html)
- Gebruik VSCode om het bestand naar GitHub te pushen.

# Notities
- De kolombreedte wordt door de browser gescaled naar de volledige pagina.
- De linkenpagina moet vanaf elke PC bereikbaar zijn. Hoewel het bestand op Dropbox staat, kan het daar vandaan niet gehost worden. Dropbox ondersteunt het renderen van html files niet meer; het Wordt Download of een Dropbox GUI.
- Verwijzen naar een file op de PC werkt niet omdat de link naar de folder op Dropbox de naam van de user bevat.  
- Opgelost door gebruik te maken van GitHub.
    - Nadeel is wel dat het dan openbaar is.
    - Voordeel is dat het vanaf elk device ongeacht de browser geopend kan worden.
- Bookmarks direct naar de files met de linken, dus niet naar de index. De oplossing door html te enbedden met iframe werkt niet goed omdat een aantal linken niet worden geopend door de gelinkte site, bijvoorbeeld O365. Hieronder de gebruikte code om de html file te embedden:  

        ```
        <body>
             <iframe src="./Linken_MASTER.html" frameborder="0" scrolling="yes" seamless="seamless"
            style="display:block; width:100%; height:100vh;"></iframe>
        </body>
        ```  

    - _N.B. Met _height:100vh_ kan je de hoogte bepalen. 100vh geeft een scrolbalk. 8b vh niet._  
        _Eventueel volgende tekst komt ver eronder te staan als je de height niet aanpast._
- Is het mogelijk om de achtergrond van de niet gevulde cellen aan te passen?
    - De achtergrond kan eventueel aangepast worden door de cellen een kleur te geven en een spatie in 1 van de cellen te zetten.
    - Om de gekleurde cellen blijft een witte rand zichtbaar; NIET DOEN, GEWOON LEEG LATEN

