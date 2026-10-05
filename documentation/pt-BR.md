<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · pt-BR · no clinical/professional/rights approval -->

# Fração de ejeção (Teichholz) e encurtamento

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/fracao-de-ejecao-teichholz)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Diâmetro diastólico do VE

`ddve`

cm · intervalo: 2–9

### Diâmetro sistólico do VE

`dsve`

cm · intervalo: 1–8

## Edição do método

Teichholz 1976:7 D³/(2,4+D); FE evolumeslineares; contexto ASEEACVI 2015 e limitaçõesgeometria

## Fórmula documentada

Volume (Teichholz) = 7 ÷ (2,4 + D) × D³ (D em cm, volume em mL)

Fração de ejeção = (VDF − VSF) ÷ VDF × 100

Fração de encurtamento = (DDVE − DSVE) ÷ DDVE × 100

## Limites e população

A estimativa de Teichholz depende da relação geométrica entre diâmetro e volume ventricular. No estudo original, a concordância foi boa sem assinergia e ruim quando havia assinergia. Doença coronariana com possível alteração regional exige cautela; a fração calculada por um diâmetro não substitui métodos apropriados à geometria ventricular.

## Referências

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
