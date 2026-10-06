<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · it · no clinical/professional/rights approval -->

# Frazione di eiezione (Teichholz) e frazione di accorciamento

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/fracao-de-ejecao-teichholz)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Diametro diastolico del ventricolo sinistro

`ddve`

cm · intervallo: 2–9

### Diametro sistolico del ventricolo sinistro

`dsve`

cm · intervallo: 1–8

## Edizione del metodo

Teichholz 1976: 7 D³/(2,4+D); FE e volumi lineari; contesto ASE/EACVI 2015 e limiti geometrici

## Formula documentata

Volume (Teichholz) = 7 ÷ (2,4 + D) × D³ (D in cm, volume in mL)

Frazione d’eiezione = (VTD − VTS) ÷ VTD × 100

Frazione di accorciamento = (DTDVS − DTSVS) ÷ DTDVS × 100

## Limiti e popolazione

La stima di Teichholz dipende dalla relazione geometrica tra diametro e volume ventricolare. Nello studio originale, l’accordo era buono in assenza di asinergia e scarso quando questa era presente. La coronaropatia con possibile alterazione regionale richiede cautela; la frazione calcolata da un solo diametro non sostituisce metodi appropriati alla geometria ventricolare.

## Riferimenti

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Frazione di eiezione preservata

| Dettagli del risultato | |
| --- | --- |
| Volume telediastolico | 118 mL |
| Volume telesistolico | 41 mL |
| Volume sistolico | 77 mL |
| Frazione di accorciamento | 36% |

