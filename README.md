# Catálogo Realmed

Catálogo de produtos em página única (`catalog.html`) para a **Realmed Distribuidora e Comercial Online Ltda** (CNPJ 50.689.350/0001-85).

## Como visualizar

Abra o arquivo `catalog.html` diretamente no navegador.

## Como adicionar as fotos reais dos produtos

Coloque os arquivos de imagem na pasta `assets/products/` usando exatamente estes nomes (um por produto já cadastrado):

| Produto                                   | Caminho do arquivo                        |
|--------------------------------------------|--------------------------------------------|
| MAG-6 (6 Magnésios)                        | `assets/products/mag-6.jpg`                 |
| Óleo de Semente de Abóbora                 | `assets/products/oleo-abobora.jpg`          |
| Óleo de Alho                                | `assets/products/oleo-alho.jpg`              |
| Vitamina B12                                | `assets/products/vitamina-b12.jpg`           |
| Carvão Vegetal Ativado + Beterraba          | `assets/products/carvao-beterraba.jpg`       |

Enquanto a imagem não existir, o cartão do produto exibe um espaço reservado tracejado indicando o caminho esperado — assim que o arquivo real for adicionado na pasta, ele aparece automaticamente, sem precisar editar o HTML.

## Como adicionar novos produtos

No arquivo `catalog.html`, dentro do array `products` (bloco `<script>`), adicione um novo objeto seguindo o mesmo padrão:

```js
{
  image: "assets/products/novo-produto.jpg",
  category: "Categoria",
  name: "Nome do Produto",
  subtitle: "Subtítulo / diferencial",
  description: "Descrição comercial do produto.",
  contains: "60 cápsulas",
  dose: "500 mg"
}
```

Coloque a foto correspondente em `assets/products/` com o mesmo nome usado em `image`. O layout do cartão (tamanho da imagem, tipografia, espaçamento) é aplicado automaticamente e permanece simétrico entre todos os produtos.
