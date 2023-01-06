# Atribuindo mais estilos às fontes

https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals

## Font-variant

- Faz variações na apresentação da fonte

```css
p {
  font-variant: small-caps;
}
```

## Font-stretch

- alargamento ou encolhimento da fonte
- aceita palavra-chaves como: expanded, condensed, normal
- aceita porcentagens de 50% a 200%

```css
p {
  font-stretch: expanded;
}
```

Nem todas as fontes aceitam o font-stretch, como nem todas as fontes aceitam tudo de tudo. kkkk

### letter-spacing

- Espaços entre caracteres

```css
p {
  letter-spacing: 4px;
}
```

### word-spacing

- Espaços entre caracteres

```css
p {
  word-spacing: 4px;
}
```

#### line-height

- Espaços entre linhas
- Pode ser com unidades ou sem unidades de medida
- Comuns: 1.5 ou 2

```css
p {
  line-height: 1.6;
}
```

##### Text-transform

_Transformação do texto_

- Valores podem ser: none | capitalize | uppercase | lowercase | full-width | full-size-kana

```css
p {
  text-transform: uppercase;
}
```

###### Text-decoration

_Aparência decorativa de um texto_

- line: underline | overline | line-through podemos aplicar mais de 1 valor

- style: wavy | dotted | double | dashed | solid

- color: <color> values

```css
h1 {
text-decoration: underline; /_ shorthand _/
}

p {
text-decoration: wavy overline blue; /_ shorthand _/
}
```

# Text-align

- Alinhamento de um texto
- Valores: start | end | left | right | center | justify | match-parent

```css
p {
  text-align: center;
}
```

## Text shadow

- Sombra aplicada a um texto
- Permite múltiplos valores

```css
p {
  text-shadow: 1px 1px 1px red, 2px 2px 1px green; /* offset-x | offset-y | blur-radius | color */
}
```

# Podemos usar o shorthand font para determinar os seguintes valores: font-style, font-variant, font-weight, font-stretch, font-size, line-height e font-family

```css
p {
  /*-style, -variant, -weight, -stretch, -size, -line-height, e -family. */
  font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}
```

https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow
https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant
https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing
https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing
https://developer.mozilla.org/en-US/docs/Web/CSS/line-height
https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform
https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration
https://developer.mozilla.org/en-US/docs/Web/CSS/text-align
https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow
