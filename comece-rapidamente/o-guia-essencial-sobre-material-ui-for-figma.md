---
description: Dicas essenciais sobre layout, container, tipografia, cores e espaçamento.
---

# O Guia Essencial Sobre Material UI for Figma

{% hint style="info" %}
ARTIGO EM DESENVOLVIMENTO.
{% endhint %}

## Layouts

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption><p>Layout básico de um app segundo o Material Design 2.</p></figcaption></figure>

O Material UI for Figma oferece diversos componentes, como Container, Box e GridV2, que ajudam na construção de qualquer layout, sem sugerir um layout específico. Já o Material Design 2 recomenda um layout básico para a criação de aplicativos, que possui três regiões principais:

1. **App bar**
2. **Navigation**
3. **Body**

### 1. App Bar

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Exemplo de app bar em dispositivos móveis.</p></figcaption></figure>

A app bar é usada para mostrar e agrupar elementos e ações importantes que ajudam os usuários a realizar tarefas principais no aplicativo. Ela organiza elementos como ícones de menu, logotipos e barras de pesquisa de forma que fiquem bem posicionados na tela. Por exemplo, o ícone do menu e o logotipo ficam na borda esquerda, a barra de pesquisa no centro, e os ícones de ação na borda direita. Essa organização garante que a app bar seja prática e funcional em diferentes tamanhos de tela.

### 2. Navigation

A região de navegação é composta por componentes e elementos que ajudam os usuários a navegar entre destinos em um aplicativo e acionar ações importantes.

* **Região de Navegação Modal (Modal Navigation Drawer)**: Em telas menores, com largura abaixo de 600 px, um drawer de navegação modal pode preencher a região de navegação, aparecendo elevado acima da região do corpo.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Navegação para telas menores que 600 px.</p></figcaption></figure>

**Região de Navegação Colapsada (Navigation rail)**: Quando a navegação está fechada, a largura da região de navegação é fixada em 72 px. Isso é usado para telas menores, onde o espaço é mais limitado.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Navegação para telas entre 600 - 900 px.</p></figcaption></figure>

**Região de Navegação Expandida (Navigation drawer)**: Quando a navegação está aberta, a largura da região de navegação é fixada em 256 px. Isso é ideal para telas maiores (>= 900 px), onde há espaço suficiente para exibir a navegação completa.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Navegação para telas com 900 px ou mais.</p></figcaption></figure>

#### **Navegação e Dimensões da Tela**

| Largura da Tela | Tipo de Navegação       | Largura da Navegação                                          |
| --------------- | ----------------------- | ------------------------------------------------------------- |
| < 600 px        | Modal Navigation Drawer | Preenche a região de navegação, aparece elevado acima do body |
| 600 px - 900 px | Navigation Rail         | 72 px (colapsada)                                             |
| >= 900 px       | Navigation Drawer       | 256 px (expandida)                                            |

### 3. Body

##

## Container

<figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption><p>O componente &#x3C;Container> e suas propriedades. Imagem obtida no <a href="https://www.figma.com/community/file/912837788133317724">Material UI Community Edition</a>.</p></figcaption></figure>

O container é utilizado para criar layouts. O componente Container no MUI for Figma é um frame que representa toda a tela, dentro do qual todo o conteúdo é desenhado.

Os nomes dos componentes no MUI for Figma começam e terminam com os símbolos de menor (<)e maior (>): \<Container>, \<Button>, etc.

### **Larguras Padrão**

O Container está disponível em 5 larguras diferentes, ideais para mobile, tablet, desktop e além. No Figma, essas larguras são fixas e definidas pela propriedade `Max Width` do componente. As larguras padrão são:

* **Extra small** (xs): 444 px
* **Small** (sm): 600 px
* **Medium** (md): 900 px
* **Large** (lg): 1220 px
* **Extra large** (xl): 1536 px

O designer pode alterar esses valores redefinindo a propriedade Width (`W`).

### **Auto Layout**

Por padrão, o Auto Layout está ativado no Container. No entanto, o designer pode desativar essa funcionalidade conforme necessário.

### **Padding Horizontal**

O Container possui uma propriedade chamada `Dis. Gutters` que, quando ativada, define o padding horizontal para um valor positivo.

### **Grid**

O Container utiliza um sistema de grid baseado em 12 colunas, que varia de acordo com a largura da tela, facilitando o design de layouts responsivos.

## Tipografia

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption><p>O texto 1 usa um estilo pré-definido do Material UI e se encaixa verticalmente no grid de 4px. O texto 2 usa um estilo personalizado que não segue as recomendações do Material Design.</p></figcaption></figure>

### Estilos de Texto

Os estilos de texto no Material UI utilizam a fonte **Roboto**, seguindo as definições tipográficas do **Material Design 2**. Esses estilos abrangem títulos (**h1..h6**), corpo de texto (**body1 e body2**), subtítulos (**subtitle1 e subtitle2**), linha superior (**overline**) e legenda (**caption**), além de estilos específicos para componentes como botões, DataPickers, menus e tabelas.

É essencial que os designers usem esses estilos padrão, pois estão diretamente relacionados ao tema do Material UI usados pelos desenvolvedores. Se precisar personalizar algum estilo, será necessário atualizar o arquivo de tema usado no desenvolvimento das aplicações React. Isso pode ser feito usando o **Material UI Sync plugin** do Figma**.**

Ao trabalhar com fontes, alinhe-as à identidade visual da marca do aplicativo. Atualize a fonte em todos os estilos mencionados para manter a coesão. O plugin do **Figma Batch Styler** facilita essa tarefa em larga escala.

Preste atenção na altura da linha ao ajustar estilos no Material UI. Essas alturas são múltiplos de 4px, garantindo um alinhamento perfeito em um grid de 4px, o que contribui para uma interface visualmente coesa e harmoniosa, alinhada às diretrizes do Material Design.

### Estilos de Texto e HTML Semântico

Os estilos de texto h1 a h6 no Material UI for Figma podem gerar confusão, pois no HTML5 esses termos têm significados específicos. No Figma, os designers usam esses títulos principalmente para criar uma hierarquia visual, não necessariamente seguindo a mesma hierarquia semântica do HTML.

No HTML, o h1 é para o título principal da página, seguido por h2 para subseções importantes, e assim por diante. Isso facilita a navegação e compreensão para pessoas com deficiência, conforme recomendações do Comitê de Acessibilidade do W3C. No Figma, o designer pode usar o estilo h1 para destacar visualmente uma seção importante, mas não necessariamente o título principal.

Por exemplo, ao projetar um site de notícias no Figma, o designer pode usar h1 para o nome do site no cabeçalho, h2 para títulos principais das notícias, h3 para subtítulos, e assim por diante. Visualmente, isso cria uma estrutura clara, mas no HTML, h1 deveria ser o título principal da página, como "Página Inicial" ou "Notícias".

Quando houver discrepância entre os estilos do Figma e a semântica HTML, o designer pode adicionar notas ao design. Por exemplo, se quiser que um texto tenha o estilo h3 no Figma, mas seja renderizado como `<h4>` no HTML, adicione uma nota explicando essa especificação. Isso garante que os desenvolvedores compreendam a intenção do design e apliquem os estilos corretamente.

### Mapeamento de Estilos de Texto para HTML5

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

### Usando os Estilos de Texto

* **Títulos (h1 - h6):** reservado para informações curtas e importantes.
* **Subtítulos (subtitle):** são menores que os títulos. Eles são tipicamente reservados para textos de ênfase média e de menor extensão.
* **Corpo de texto (body):** tipicamente usado para escrita de formato longo, pois funciona bem em tamanhos de texto pequenos.
* **Legenda e Linha Superior (caption e overline):** texto de legenda e linha superior são os tamanhos de fonte mais pequenos. Eles são usados parcimoniosamente para anotar imagens ou introduzir um título.

## Para Saber Mais

* [A escala tipográfica no Material Design 2](https://m2.material.io/design/typography/the-type-system.html#type-scale)
* [O componente Typography no Material UI](https://mui.com/material-ui/react-typography/)
* [Plugin Batch Styler para o Figma](https://www.figma.com/community/plugin/818203235789864127/batch-styler)
* [Plugin Material UI Sync para o Figma](https://www.figma.com/community/plugin/1336346114713490235/material-ui-sync)





