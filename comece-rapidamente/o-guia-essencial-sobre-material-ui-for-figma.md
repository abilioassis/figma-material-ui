# O Guia Essencial Sobre Material UI for Figma

### Tipografia e Estilos de Texto

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>O texto 1 usa um estilo pré-definido do Material UI e se encaixa verticalmente no grid de 4px. O texto 2 usa um estilo personalizado que não segue as recomendações do Material Design.</p></figcaption></figure>

Os estilos de texto no Material UI utilizam a fonte Roboto, seguindo as definições tipográficas do Material Design 2. Esses estilos abrangem títulos (h1..h6), corpo de texto (body1 e body2), subtítulos (subtitle1 e subtitle2), linha superior (overline) e legenda (caption), além de estilos específicos para componentes como botões, DataPickers, menus e tabelas.

É essencial que os designers usem esses estilos padrão, pois estão diretamente integrados ao tema do Material UI no Figma. Se precisar personalizar algum estilo, atualize o arquivo de tema usado pelos desenvolvedores nas aplicações React.

Ao trabalhar com fontes, alinhe-as à identidade visual da marca do aplicativo. Atualize a fonte em todos os estilos mencionados para manter a coesão. O plugin **Figma Batch Styler** facilita essa tarefa em larga escala.

Preste atenção na altura da linha ao ajustar estilos no Material UI. Essas alturas são múltiplos de 4px, garantindo um alinhamento perfeito em um grid de 4px, o que contribui para uma interface visualmente coesa e harmoniosa, alinhada às diretrizes do Material Design.

### Estilos de Texto e HTML Semântico

Os estilos de texto h1 a h6 no Material UI for Figma podem ser confusos. No HTML5, esses termos têm significados específicos e seguem boas práticas do W3C. No Figma, os designers usam esses títulos principalmente para criar uma hierarquia visual, não necessariamente seguindo a mesma hierarquia semântica do HTML.

No HTML, o h1 é para o título principal da página, seguido por h2 para subseções importantes, e assim por diante. Isso facilita a navegação e compreensão para pessoas com deficiência, conforme recomendações do Comitê de Acessibilidade do W3C. No Figma, o designer pode usar o estilo h1 para destacar visualmente uma seção importante, mas não necessariamente o título principal.

Por exemplo, ao projetar um site de notícias no Figma, o designer pode usar h1 para o nome do site no cabeçalho, h2 para títulos principais das notícias, h3 para subtítulos, e assim por diante. Visualmente, isso cria uma estrutura clara, mas no HTML, h1 deveria ser o título principal da página, como "Página Inicial" ou "Notícias".

Quando houver discrepância entre os estilos do Figma e a semântica HTML, o designer pode adicionar notas ao design. Por exemplo, se quiser que um texto tenha o estilo h3 no Figma, mas seja renderizado como `<h4>` no HTML, adicione uma nota explicando essa especificação. Isso garante que os desenvolvedores compreendam a intenção do design e apliquem os estilos corretamente.

### Mapeamento de Estilos para HTML no Material UI

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

Embora o Material Design 3 redefina completamente os estilos de texto, o Material UI (versão 5.15.X) segue as diretrizes do Material Design 2

Casos de uso para cada estilo.

Embora já esteja disponível a versão 3, a versão atual do Material UI (5.15.X) está alinhada às definições do Marial Design 2 (versão 2: M2).





## Espaçamento

## Cores

## Modos Light e Dark



Para Saber Mais

* [Plugin Batch Styler para o Figma.](https://www.figma.com/community/plugin/818203235789864127/batch-styler)



