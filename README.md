Appunti Algebra 2014
====================

Appunti del corso di Algebra (primo canale, prof.ssa Venezia, II anno laurea in Informatica 2014/2015, Sapienza)

Struttura degli appunti:

- `concetti_base.tex`: teoria degli insiemi, relazioni, funzioni, numeri naturali e principio di induzione, calcolo combinatorio
- `strutture.tex`: monoidi, gruppi, anelli, campi. anello degli interi, anello degli interi modulo _n_, anello dei polinomi, anello delle matrici quadrate
- `spazi_vettoriali.tex`: spazi vettoriali, polinomi, matrici, vettori geometrici, _n_-uple
- `risoluzione.tex`
- `applicazioni.tex`

### Package

Dovrebbe essere possibile compilare i singoli file, con i dovuti accorgimenti. I package necessari _dovrebbero_ essere:

- `amsmath`, `amsthm`, `amsfonts`, `amssymb`
- `mathtools`
- `centernot`
- `pgfplots`
- `xcolor` (ho colorato le celle di alcune tabelle)

### Ambienti

I tipi di teorema definiti dovrebbero essere: `theorem`, `lem`, `prop`, `cor`, `defn`, `exmp`, `oss`, `caso`, `esercizio`.

Uso un environment `smallpmatrix` basato su `smallmatrix` per matrici altrimenti troppo invadenti.

### Operatori

Simbolo di "copre":

    \newcommand{\covers}{<\!\cdot}

Unione disgiunta:

    \newcommand{\dotcup}{\mathaccent\cdot\cup}

Relazione di equivalenza sulle classi laterali:

    \newcommand{\lateralsx}[1]{{}_{#1}\!\sim}
    \newcommand{\lateraldx}[1]{\sim_{#1}}

Minimo comune multiplo e massimo comun denominatore:

    \newcommand{\mcm}{\text{mcm}}
    \newcommand{\mcd}{\text{MCD}}

Sottogruppo delle potenze di un elemento:

    \newcommand{\pow}[1]{<\!{#1}\!>}

Cardinalità:

    \newcommand{\abs}[1]{\left\lvert{#1}\right\rvert}

Operatore di "divide":

    \newcommand{\divides}{\mid}

Elemento neutro:

    \newcommand{\nullelement}{\underline{0}}

Altri operatori, viva l'approccio semantico:

- `\subgroupset`, una _S_ corsiva, per indicare l'insieme delle sottostrutture di una struttura
- `\naturals`, `\integers`, `\rationals`, `\reals`, `\complexes`, lettere rappresentative degli insiemi numerici, e `\field` e `\subfield` per indicare campi e sottocampi generici
- `\matrices`, una _fancy M_ per indicare un insieme di matrici
- `\supop` e `\infop` per le operazioni di _inf_ e _sup_, simili all'`and` e all'`or` logico

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Appunti Algebra 2014</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://asmeikal.me" property="cc:attributionName" rel="cc:attributionURL">Michele Laurenti</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
