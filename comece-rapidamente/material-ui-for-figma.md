# Material UI for Figma

## Espaçamento

Conceitos Básicos de Espaçamento

Personalizando a Escala de Espaçamento do Material UI

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Valores de espaçamento padrão no Material UI for Figma</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Criação de uma nova linha na tabela de espaçamento do Material UI for Figma</p></figcaption></figure>



| **Tipo do Componente** | **Variante** | **Casos de Uso**                                                             | **Principais Propriedades**                                                                                                                                                  |
| ---------------------- | ------------ | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Typography             | overline     | <p>- Rótulos de seções<br>- Descrições curtas<br>- Indicadores de estado</p> | <p>- <strong>font-size:</strong> 10px<br>- <strong>line-height:</strong> 1.6<br>- <strong>letter-spacing:</strong> 1.5px<br>- <strong>text-transform:</strong> uppercase</p> |

#### Descrição das Principais Propriedades

* **font-size:** Define o tamanho da fonte, que é geralmente menor para a variante overline para manter a discrição.
* **line-height:** Define a altura da linha, proporcionando um espaçamento adequado entre linhas de texto.
* **letter-spacing:** Ajusta o espaçamento entre letras, comumente aumentado para a variante overline para melhorar a legibilidade.
* **text-transform:** Aplica a transformação de texto, frequentemente definida como uppercase para destacar a overline de maneira sutil.

Essa tabela resume as características principais da variante **Overline**, destacando seus usos e propriedades chave para facilitar o design e a implementação em projetos utilizando o Material UI.

<mark style="color:green;">`POST`</mark> `/users`

\<Description of the endpoint>

**Headers**

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Bearer <token>`   |

**Body**

| Name   | Type   | Description      |
| ------ | ------ | ---------------- |
| `name` | string | Name of the user |
| `age`  | number | Age of the user  |

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "id": 1,
  "name": "John",
  "age": 30
}
```
{% endtab %}

{% tab title="400" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="JavaScript" %}
```javascript
const message = "hello world";
console.log(message);
```
{% endtab %}

{% tab title="Python" %}
```python
message = "hello world"
print(message)
```
{% endtab %}

{% tab title="Ruby" %}
```ruby
message = "hello world"
puts message
```
{% endtab %}
{% endtabs %}



{% embed url="https://whimsical.com/modelo-de-conteudo-SdhQXraHbLV1GBzmvfxLBj" %}
