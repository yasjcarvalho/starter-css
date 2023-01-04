# Page Layouts

- Tables
- Floats e Clear
- Framework e Grid Systems
- Flexbox
- Grid

## Posicionamentos

Controlar onde, na página, o elemento irá ficar, alterando o fluxo normal dos elementos.

- Name: position
- Value: static|relative|absolute|fixed

### Colocando em prática

# # Relative

1. No documento style.css, criei 3 caixas e por si só elas já são estáticas (static).
   Adicionei o "position: relative;" na box1, "left: 100px;" e "top: 80px;"
   Assim, observo que a box1 não atrapalha o fluxo do resto.

Lidera 5 propriedades:

- top, right, left, bottom, z-index

# # Absolute

1. Ao colocar o "position: absolute;", criamos uma camada para o box1 acima das outras.
   Observo que os box2 e box3 voltam a ocupar o fluxo normal "static" e o box1 começa a ocupar um novo fluxo.

2. O elemento position absolute é posicionado em relação ao seu parent element mais próximo. Se ele elemento "pai" não existir, ele será posicionado em relação ao bloco contento a raiz do elemento.
   Ou seja, o box1 vai ser absoluto referente a sua página toda: tente com "top: 0px;" observa-se que ele gruda no top.

3. Ao adicionar um elemento "main", o box1 continua absoluto a página. Teste: Coloque todas as divs dentro do "main" e no css coloque
   main {
   margin-top: 200px;
   }

4. Entretanto, se colocarmos que o main é relative:
   main {
   margin-top: 200px;
   position: relative;
   } o box1 fica sob o box2 e adere as configurações do main.

Também lidera 5 propriedades:

- top, right, left, bottom, z-index

# # Fixed

# # Element Stacking
