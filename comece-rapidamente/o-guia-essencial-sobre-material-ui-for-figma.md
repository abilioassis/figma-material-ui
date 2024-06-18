---
description: <EM DESENVOLVIMENTO>
---

# O Guia Essencial Sobre Material UI for Figma

## Tipografia e Estilos de Texto

Os estilos de texto no Material UI utilizam a fonte **Roboto**, alinhando-se às definições tipográficas do Material Design 2. Esses estilos abrangem desde títulos (h1..h6) até elementos como corpo de texto (body1 e body2), subtítulos (subtitle1 e subtitle2), linha superior (overline) e legenda (caption). Adicionalmente, há estilos específicos para componentes como botões, DataPickers, menus, tabelas, entre outros.

É crucial que os designers usem esses estilos padrão, pois eles estão diretamente integrados ao tema do Material UI no Figma. Caso seja necessário personalizar algum estilo, é essencial atualizar o arquivo de tema utilizado pelos desenvolvedores na construção das aplicações React.

Ao trabalhar com fontes, é comum alinhá-las à identidade visual da marca para a qual o aplicativo está sendo desenvolvido. Para manter essa coesão, é importante atualizar a fonte em todos os estilos mencionados. O plugin do Figma Batch Styler pode ser uma ferramenta eficaz para aplicar estilos de forma rápida e precisa em larga escala.

Além disso, ao ajustar os estilos no Material UI, prestar atenção na altura da linha é fundamental. No Material UI, as alturas das linhas são múltiplos de 4px, garantindo um alinhamento perfeito em um grid de 4px. Isso não só contribui para uma interface visualmente coesa, mas também adere às diretrizes do Material Design, proporcionando uma experiência harmoniosa e consistente para os usuários.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>O texto 1 usa um estilo pré-definido do Material UI e se encaixa verticalmente no grid de 4px. O texto 2 usa um estilo personalizado que não segue as recomendações do Material Design.</p></figcaption></figure>

### Estilos de Texto e HTML Semântico

Quando falamos sobre os estilos h1 a h6 no Material UI for Figma, é importante entender que no HTML5 esses termos têm um significado específico e seguem boas práticas recomendadas pelo W3C. No entanto, no Figma, os designers utilizam esses títulos principalmente para criar uma hierarquia visual no design, não necessariamente seguindo a mesma hierarquia semântica que o HTML propõe.

Por exemplo, no HTML, o h1 é tradicionalmente utilizado para o título principal de uma página, seguido pelo h2 para subseções importantes, e assim por diante. Isso segue as diretrizes de acessibilidade e estruturação de conteúdo do W3C WAI, que recomendam o uso correto e consistente dessas tags para facilitar a compreensão e a navegação para pessoas com deficiência.

No entanto, no Figma, o designer pode usar o h1 para um elemento que visualmente destaque uma seção importante, mas não necessariamente corresponda ao título principal do conteúdo. Isso significa que, embora a hierarquia visual seja mantida para guiar a leitura e a compreensão do design, ela pode não estar alinhada com a hierarquia semântica do HTML.

#### Exemplo Prático

Imagine que estamos projetando um site de notícias no Figma. O designer pode usar o h1 para destacar o nome do site no cabeçalho, o h2 para os títulos principais das notícias, o h3 para os subtítulos das notícias, e assim por diante. Visualmente, isso cria uma estrutura clara e organizada para o design, mas no HTML, o h1 deveria ser reservado para o título principal da página, como "Página Inicial" ou "Notícias".

#### Recomendações do W3C WAI

Para seguir as melhores práticas de acessibilidade e estruturação de conteúdo, o W3C WAI recomenda:

* **h1**: Deve ser utilizado apenas uma vez por página e representar o título principal do conteúdo.
* **h2** a **h6**: Devem ser usados para subseções e títulos hierarquicamente menores, seguindo uma ordem lógica e consistente.

Ao entender essa diferença entre a hierarquia visual no Figma e a hierarquia semântica no HTML, os designers podem criar designs eficazes e acessíveis, alinhando a estrutura do conteúdo tanto visualmente quanto semanticamente.

Ao utilizar o Material UI no Figma, o designer tem à disposição um conjunto de estilos de texto pré-definidos que correspondem a tags HTML específicas, seguindo o mapeamento padrão que mencionamos anteriormente. No entanto, caso o designer deseje usar um mapeamento diferente do padrão, ele pode fazê-lo adicionando notas ao seu design.

Por exemplo, se o designer quer que um texto tenha o estilo de um título secundário (correspondente a `Typography variant="h3"` no Material UI), mas prefere que ele seja renderizado como um título terciário no HTML (correspondente a `<h4>`), ele pode adicionar uma nota indicando essa especificação. Isso ajuda a garantir que os desenvolvedores entendam a intenção por trás do design e possam aplicar os estilos corretamente durante o desenvolvimento da aplicação.

Essas notas podem ser adicionadas de diversas formas, como através de anotações diretamente no Figma, comentários explicativos nos componentes de texto, ou até mesmo em documentos de especificação de design compartilhados com a equipe de desenvolvimento. O importante é comunicar de forma clara e precisa qualquer desvio do mapeamento padrão para garantir a consistência e a fidelidade do design durante a implementação.















Como alterar a fonte para refletir as definições da minha marca?

O que deve e não se deve alterar?

Separação entre estilos no Figma e semântica HTML.

Casos de uso para cada estilo.

Embora já esteja disponível a versão 3, a versão atual do Material UI (5.15.X) está alinhada às definições do Marial Design 2 (versão 2: M2).





## Espaçamento

## Cores

## Modos Light e Dark



Para Saber Mais

* [Plugin Batch Styler para o Figma.](https://www.figma.com/community/plugin/818203235789864127/batch-styler)



