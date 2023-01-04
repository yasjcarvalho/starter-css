# Trabalhando com fontes

Tipografia transmite mensagem

- negrito
- tamanho
- estilo

---

## Basic Font Froperties

- font-family
- font-weight
- font-style
- font-size

---

### Font Family

- Tipo de fonte de um elemento
- Lista de fontes e ordem de prioridade
- inclui _fallback_ font

1. Ideia de fallback abaixo, se não tiver a primeira, então procura a segunda e assim por diante.

```css
p {
  font-family: 'Times New Roman', Times, serif;
}
```

---

- serif: fontes que tem dobrinha abaixo/linha abaixo bem sutil
- sans: não tem dobrinha

# # Font Weight

- Peso da fonte

```css
p {
  font-weight: bold; /*normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900 */
}
```

Dependendo da família da fonte, não podemos acessar todos os pesos, tá?

---

# # # Font Style

- O estilo da fonte

```css
span {
  font-style: italic; /*normal italic oblique*/
}
```

---

#### Font Size

- Tamanho da fonte

```css
p {
  font-size: 18px; /*em rem */
}
```

---

##### Web Fonts

- Fontes do sistema x Fontes da web

Fontes do sistema são as fontes que estão instaladas na máquina do usuário e nem sempre o cliente vai ter instalado as fontes usadas no projeto e isso pode fazer com que os estilos dos textos não sejam aplicados corretamente, mas para resolver esses casos podemos preparar nossas fonts para web ou usar fontes da web.

- Como usar fontes para web?
  @font-face
  @import
  link

---

- Referência:
  https://www.w3.org/TR/css-fonts-3/

https://fonts.google.com/ https://css-tricks.com/snippets/css/using-font-face-in-css/

---
