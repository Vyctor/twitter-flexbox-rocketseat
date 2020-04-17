# Flexbox

Para trabalharmos com flexbox precisamos utilizar

```css
display: flex;
```

no elemento que estiver por fora dos elementos que queremos alinhar.

## `flex-direction`

Por padrão essa propriedade assume o valor `row`, alinhamento em linha. Essa propriedade serve para mudar o direcionamento do elemento que estiver utilizando `display: flex`;

## Alinhamento

## `align-items`

Quando utilizamos flex direction row, essa propriedade vai alinhar os itens verticalmente. Por padrão seu valor é `flex-start`. Quando utilizando flex direction column ele alinha os itens horizontalmente.

## `justify-content`

Quando utilizamos flex direction row, essa propriedade vai alinhar os itens horizontalmente. Por padrão seu valor é `flex-start`. Quando utilizando flex direction column ele alinha os itens horizontalmente.

## `flex-grow`

O elemento se expande para ocupar o tamanho da tela.

## `flex-shrink`

O elemento se reduz para caber na tela.

## `flex`

é a soma do `flex-grow` e do `flex-shrink`

## `flex-wrap`

Ele quebra a linha quando o elemento não couber inteiro

## `align-content`

alinha os elementos quando eles ocupam uma linha quebrada (mais de uma linha). Possui as mesmas propriedades do `justify-content`
