# Appunti di Meccanica dei Fluidi
Questa repository contiene appunti di Meccanica dei Fluidi, realizzati a partire dal corso di *Meccanica dei Fluidi* tenuto dal professor Paolo Luchini nell'A.A. 2020/21 presso l'Università degli Studi di Salerno.

**Questi appunti non sono da ritenersi in alcun modo approvati/avallati/etc dal docente**
Allo stesso modo non sono in alcun modo materiale raccomandato ufficialmente per lo studio del corso: punto di riferimento sono e rimangono i libri di testo scelti dal docente e le lezioni in aula.

Vengono resi pubblici nella speranza che possano essere per qualche studente un aiuto nello studio della meccanica dei fluidi, ma ribadisco che nel caso non sono da prendersi come unico materiale di riferimento.

## Download
Per scaricare gli appunti, vedere nella sezione [Release][release-link], oppure [cliccare qui per il download diretto del PDF dell'ultima versione][latest-release].

[release-link]: https://github.com/f-dinucci/appuntiMeccanicaFluidi/releases
[latest-release]: https://github.com/f-dinucci/appuntiMeccanicaFluidi/releases/download/release/Appunti.di.Meccanica.dei.Fluidi.2021-04-21.pdf

## Istruzioni di compilazione da sorgente
Istruzioni nel caso si voglia provare a compilare gli appunti dai sorgenti LaTeX (ad esempio per provare delle modifiche prima di suggerirle).
Normalmente non è necessario, basta utilizzare i file di cui nella sezione __Download__.

### Prerequisiti
Per realizzare questi appunti è stato utilizzato [TeX Live](https://www.tug.org/texlive/) (disponibile per sistemi [Linux](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz) e [Windows](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe)), si consiglia di utilizzare come _installation scheme_ "scheme-full".

L'obiettivo è mantenere la compatibilità con la versione più recente di TeX Live, attualmente la 2021 (precedentemente è stata utilizzata la 2020).
La compilazione _dovrebbe_ funzionare anche su altre distribuzioni TeX e su versioni precedenti di TeX Live, ma non è stata testata.

Riferimenti utili:
* [TeX Live UNIX Quick Install](https://www.tug.org/texlive/quickinstall.html)
* [TeX Live Windows Quick Install](https://www.tug.org/texlive/windows.html)
* [TeX Live full install documentation](https://www.tug.org/texlive/doc/texlive-en/texlive-en.html#x1-140003)

### Compilazione

#### Interfaccia grafica (TeXworks)

* Aprire AppuntiMeccanicaDeiFluidi.tex in TeXworks e dare il comando di _Typeset_ come pdfLaTeX 
* Al termine dare _Typeset_ come Biber
* Dare nuovamente il comando di _Typeset_ come pdfLaTeX
* Saranno generati diversi file, di questi __AppuntiMeccanicaDeiFluidi.pdf__ è quello desiderato.

#### Riga di comando
Aprire un terminale, spostarsi nella cartella in cui si trova il file _AppuntiMeccanicaDeiFluidi.tex_ e dare i seguenti comandi:
```
	pdflatex AppuntiMeccanicaDeiFluidi.tex
	biber AppuntiMeccanicaDeiFluidi
	pdflatex AppuntiMeccanicaDeiFluidi.tex
``` 
Saranno generati diversi file, di questi __AppuntiMeccanicaDeiFluidi.pdf__ è quello desiderato.

## Licenza
I sorgenti LaTeX/IPE, i file da essi generati, il testo e le immagini incluse sono (salvo nel caso di parti ove sia diversamente ed esplicitamente specificato oppure non applicabile) rilasciate sotto licenza [Creative Commons Attribution-ShareAlike 4.0 International][cc-by-sa].
Una copia della licenza è inclusa nella repository stessa come [LICENSE.md/LICENSE.md](./LICENSE.md/LICENSE.md).

[cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/legalcode
