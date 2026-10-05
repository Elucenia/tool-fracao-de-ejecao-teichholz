<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · en · no clinical/professional/rights approval -->

# Ejection fraction (Teichholz) and fractional shortening

[conditions, sources and permissions](https://elucenia.org/en/tools/fracao-de-ejecao-teichholz)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Left ventricular diastolic diameter

`ddve`

cm · range: 2–9

### Left ventricular systolic diameter

`dsve`

cm · range: 1–8

## Method edition

Teichholz 1976: 7 D³/(2.4+D); EF and linear volumes; ASE/EACVI 2015 context and geometric limitations

## Documented formula

Volume (Teichholz) = 7 ÷ (2.4 + D) × D³ (D in cm, volume in mL)

Ejection fraction = (EDV − ESV) ÷ EDV × 100

Fractional shortening = (LVEDD − LVESD) ÷ LVEDD × 100

## Limits and population

The Teichholz estimate depends on the geometric relationship between ventricular diameter and volume. In the original study, agreement was good without asynergy and poor when asynergy was present. Coronary disease with possible regional abnormalities requires caution; the fraction calculated from one diameter does not replace methods suited to ventricular geometry.

## References

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
