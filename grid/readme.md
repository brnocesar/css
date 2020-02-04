# Grid
Com este sistema de layout podemos manipular a página de forma **bidimensional**, dividindo-a em linhas e colunas.

Suas propriedades são separadas em dois grupos: as dos `contêineres` e dos `itens`.

#### Container
```css
.container {
    display: grid;
    grid-template-columns: ;
    grid-template-rows: ;
    grid-template-areas: ;
    grid-gap: ;
}
```

#### Item
```css
.item {
    display: grid;
    grid-column: ;
    grid-row: ;
    grid-area: ;
}
```

## Propriedades de alinhamento
Podem ser utilizados tanto nos `contêineres` como nos `itens`, e são as seguintes:

```css
.alinhamento {
    justify-content: ;
    align-content: ;
    justify-items: ;
    align-items: ;
    justify-self: ;
    align-self: ;
}
```
### `justify` e `align`
Estas propriedades dizem respeito aos eixos x e y, respectivamente.
- `justify`: é o posicionamento horizontal, da esquerda para direita;
- `align`: representa o posicionamento vertical, de cima para baixo.

#### `content`
Permite alinhar o próprio grid no espaço que lhe é destinado. As propriedades `justify-content` e `align-content` aceitam sete valores:
- `start`:
- `end`:
- `center`:
- `stretch`:
- `space-between`:
- `space-around`:
- `space-evenly`:

#### `items`
Permite alinhar os `items` do grid no espaço disponível na célula que ele estiver. As propriedades `justify-items` e `align-items` aceitam os seguintes valores:
- `start`:
- `end`:
- `center`:
- `stretch`:

#### `self`
Possui o mesmo comportamento de `items`, mas o estilo é aplicado no próprio elemento e não no container. As propriedades `justify-self` e `align-self` aceitam os mesmos valores de `items`:
- `start`:
- `end`:
- `center`:
- `stretch`: