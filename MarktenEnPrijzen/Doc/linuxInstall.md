# Samenvatting Bouwen op Linux/OSX

Je zal de volgende dingen nodig hebben:
* [git](http://www.git-scm.com/)
* [texlive](https://www.tug.org/texlive/)
* ([make](https://www.gnu.org/software/make/))

Installeer deze programma's, make is optioneel. Ga dan naar je terminal en voer volgende commando's uit:

``` bash
cd /your/preferred/directory
git clone https://github.com/HerrSubset/SamenvattingMarktenEnPrijzen
cd SamenvattingMarktenEnPrijzen
```

Indien make op je systeem geïnstalleerd is, kan je vervolgens volgend commando intypen:
```bash
make
```

Er zal nu een nieuwe map verschijnen genaamd "helpFiles". De samenvatting zelf verschijnt als "Summary.pdf" in de root folder van het project.

Indien je make niet hebt, kan je texlive rechtstreeks aanroepen. Volgend commando zal dan je samenvatting creëren:
``` bash
pdflatex -jobname Summary.pdf main.tex
```

Dit commando zal je tweemaal moeten uitvoeren om alle referenties binnen het document juist te krijgen.
