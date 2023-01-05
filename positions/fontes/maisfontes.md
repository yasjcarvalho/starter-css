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

https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant
https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing
https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing
https://developer.mozilla.org/en-US/docs/Web/CSS/line-height
