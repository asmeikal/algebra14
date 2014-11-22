Appunti Algebra 2014
====================

Appunti del corso di Algebra (primo canale, prof.ssa Venezia, II anno laurea in Informatica 2014/2015, Sapienza)

Struttura degli appunti:
- file principale, include gli altri:
    - `concetti_base.tex`: teoria degli insiemi, relazioni, funzioni, numeri naturali e principio di induzione, calcolo combinatorio
    - `strutture.tex`: gruppi, anelli, campi
    - `spazi_vettoriali.tex`
    - `risoluzione.tex`
    - `applicazioni.tex`

### Package

_Dovrebbe_ essere possibile compilare i singoli file, con i dovuti accorgimenti. I package necessari _dovrebbero_ essere:

- `nameref`
- `hyperref`
- `amsmath`
- `amsthm`
- `amsfonts`
- `centernot`
- `pgfplots`

I tipi di teorema definiti dovrebbero essere: `theorem`, `lem`, `prop`, `cor`, `defn`, `exmp`, `oss`.

=======
### Operatori

Simbolo di "copre":

    \newcommand{\covers}{<\!\cdot}

Unione disgiunta:

    \newcommand{\dotcup}{\mathaccent\cdot\cup}

Relazione di equivalenza sulle classi laterali:

    \newcommand{\lateralsx}[1]{{}_{#1}\!\sim}
    \newcommand{\lateraldx}[1]{\sim_{#1}}

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Appunti Algebra 2014</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://asmeikal.me" property="cc:attributionName" rel="cc:attributionURL">Michele Laurenti</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
