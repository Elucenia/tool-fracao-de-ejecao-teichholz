<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · es · no clinical/professional/rights approval -->

# Fracción de eyección (Teichholz) y acortamiento

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/fracao-de-ejecao-teichholz)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Diámetro diastólico del ventrículo izquierdo

`ddve`

cm · intervalo: 2–9

### Diámetro sistólico del ventrículo izquierdo

`dsve`

cm · intervalo: 1–8

## Edición del método

Teichholz 1976: 7 D³/(2,4+D); FE y volúmenes lineales; contexto ASE/EACVI 2015 y límites geométricos

## Fórmula documentada

Volumen (Teichholz) = 7 ÷ (2,4 + D) × D³ (D en cm, volumen en mL)

Fracción de eyección = (VTD − VTS) ÷ VTD × 100

Fracción de acortamiento = (DTDVI − DTSVI) ÷ DTDVI × 100

## Límites y población

La estimación de Teichholz depende de la relación geométrica entre diámetro y volumen ventricular. En el estudio original, la concordancia fue buena sin asinergia y mala cuando existía asinergia. La enfermedad coronaria con posible alteración regional exige cautela; la fracción calculada a partir de un diámetro no sustituye métodos adecuados para la geometría ventricular.

## Referencias

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Fracción de eyección preservada

| Detalles del resultado | |
| --- | --- |
| Volumen telediastólico | 118 mL |
| Volumen telesistólico | 41 mL |
| Volumen sistólico | 77 mL |
| Fracción de acortamiento | 36% |

