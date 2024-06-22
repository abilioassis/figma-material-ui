---
description: >-
  Dicas essenciais sobre tipografia, espaçamento, cores e como trabalhar com os
  modos claro e escuro.
---

# O Guia Essencial Sobre Material UI for Figma

## Breakpoints

São pontos definidos onde o layout muda para se adaptar a diferentes tamanhos de tela, como em celulares, tablets e desktops. No Material UI são definidos 5 breakpoints:

* `xs` extra-small: 0.
* `sm` small: 600px.
* `md` medium: 900px.&#x20;
* `lg` large: 1200px.
* `xl` extra-large: 1536px.

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption><p>Breakpoints padrão no Material UI</p></figcaption></figure>

## Grids

## Tipografia e Estilos de Texto

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>O texto 1 usa um estilo pré-definido do Material UI e se encaixa verticalmente no grid de 4px. O texto 2 usa um estilo personalizado que não segue as recomendações do Material Design.</p></figcaption></figure>

Os estilos de texto no Material UI utilizam a fonte **Roboto**, seguindo as definições tipográficas do **Material Design 2**. Esses estilos abrangem títulos (**h1..h6**), corpo de texto (**body1 e body2**), subtítulos (**subtitle1 e subtitle2**), linha superior (**overline**) e legenda (**caption**), além de estilos específicos para componentes como botões, DataPickers, menus e tabelas.

É essencial que os designers usem esses estilos padrão, pois estão diretamente relacionados ao tema do Material UI usados pelos desenvolvedores. Se precisar personalizar algum estilo, será necessário atualizar o arquivo de tema usado no desenvolvimento das aplicações React. Isso pode ser feito usando o **Material UI Sync plugin** do Figma**.**

Ao trabalhar com fontes, alinhe-as à identidade visual da marca do aplicativo. Atualize a fonte em todos os estilos mencionados para manter a coesão. O plugin do **Figma Batch Styler** facilita essa tarefa em larga escala.

Preste atenção na altura da linha ao ajustar estilos no Material UI. Essas alturas são múltiplos de 4px, garantindo um alinhamento perfeito em um grid de 4px, o que contribui para uma interface visualmente coesa e harmoniosa, alinhada às diretrizes do Material Design.

## Estilos de Texto e HTML Semântico

Os estilos de texto h1 a h6 no Material UI for Figma podem gerar confusão, pois no HTML5 esses termos têm significados específicos. No Figma, os designers usam esses títulos principalmente para criar uma hierarquia visual, não necessariamente seguindo a mesma hierarquia semântica do HTML.

No HTML, o h1 é para o título principal da página, seguido por h2 para subseções importantes, e assim por diante. Isso facilita a navegação e compreensão para pessoas com deficiência, conforme recomendações do Comitê de Acessibilidade do W3C. No Figma, o designer pode usar o estilo h1 para destacar visualmente uma seção importante, mas não necessariamente o título principal.

Por exemplo, ao projetar um site de notícias no Figma, o designer pode usar h1 para o nome do site no cabeçalho, h2 para títulos principais das notícias, h3 para subtítulos, e assim por diante. Visualmente, isso cria uma estrutura clara, mas no HTML, h1 deveria ser o título principal da página, como "Página Inicial" ou "Notícias".

Quando houver discrepância entre os estilos do Figma e a semântica HTML, o designer pode adicionar notas ao design. Por exemplo, se quiser que um texto tenha o estilo h3 no Figma, mas seja renderizado como `<h4>` no HTML, adicione uma nota explicando essa especificação. Isso garante que os desenvolvedores compreendam a intenção do design e apliquem os estilos corretamente.

## Mapeamento de Estilos Figma para HTML

| Figma     | HTML   |
| --------- | ------ |
| h1        | `<h1>` |
| h2        | `<h2>` |
| h3        | `<h3>` |
| h4        | `<h4>` |
| h5        | `<h5>` |
| h6        | `<h6>` |
| subtitle1 | `<h6>` |
| subtitle2 | `<h6>` |
| body1     | `<p>`  |
| body2     | `<p>`  |

## Como Usar os Estilos de Texto

* **Títulos (h1 - h6):** reservado para informações curtas e importantes.
* **Subtítulos (subtitle):** são menores que os títulos. Eles são tipicamente reservados para textos de ênfase média e de menor extensão.
* **Corpo de texto (body):** tipicamente usado para escrita de formato longo, pois funciona bem em tamanhos de texto pequenos.
* **Legenda e Linha Superior (caption e overline):** texto de legenda e linha superior são os tamanhos de fonte mais pequenos. Eles são usados parcimoniosamente para anotar imagens ou introduzir um título.

## Espaçamento

## Cores

## Modos Claro e Escuro

## Para Saber Mais

* [A escala tipográfica no Material Design 2](https://m2.material.io/design/typography/the-type-system.html#type-scale)
* [O componente Typography no Material UI](https://mui.com/material-ui/react-typography/)
* [Plugin Batch Styler para o Figma](https://www.figma.com/community/plugin/818203235789864127/batch-styler)
* [Plugin Material UI Sync para o Figma](https://www.figma.com/community/plugin/1336346114713490235/material-ui-sync)





