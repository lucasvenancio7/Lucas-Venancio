# Catálogos

Este repositório reúne catálogos em página única (HTML, abertos direto no navegador).

## Catálogo Realmed

Catálogo de produtos em página única (`catalog.html`) para a **Realmed Distribuidora e Comercial Online Ltda** (CNPJ 50.689.350/0001-85).

## Como visualizar

Abra o arquivo `catalog.html` diretamente no navegador.

## Como adicionar a logo da marca (marca d'água)

Coloque o arquivo da logo em:

```
assets/branding/logo.png
```

Assim que esse arquivo existir, ele passa a aparecer automaticamente em dois lugares:
- como **marca d'água** de baixa opacidade atrás de todo o catálogo;
- como **selo circular** no cabeçalho, ao lado do nome da marca.

Enquanto o arquivo não existir, o catálogo usa um texto "REALMED" no lugar da marca d'água, sem quebrar o layout.

## Como adicionar as fotos reais dos produtos

Exporte cada foto do Canva em **1080 × 1080 px** (formato quadrado) e salve em `assets/products/` usando exatamente estes nomes:

| Produto                                    | Caminho do arquivo                              |
|----------------------------------------------|--------------------------------------------------|
| 6-Magnésios 500 mg                          | `assets/products/6-magnesios.jpg`                 |
| Vitamina B12 350 mg                         | `assets/products/vitamina-b12.jpg`                |
| Óleo de Semente de Abóbora 1 g              | `assets/products/oleo-abobora.jpg`                |
| Óleo de Alho 500 mg                         | `assets/products/oleo-alho.jpg`                   |
| Resveratrol 1 g                             | `assets/products/resveratrol.jpg`                 |
| Ômega 3 1 g (660 EPA / 360 DHA)              | `assets/products/omega-3.jpg`                     |
| Colágeno Tipo 2 80 mg                       | `assets/products/colageno-tipo-2.jpg`             |
| Maca Peruana 500 mg                         | `assets/products/maca-peruana.jpg`                |
| Maca Negra 500 mg                           | `assets/products/maca-negra.jpg`                  |
| Maca Peruana + Creatina 500 mg              | `assets/products/maca-peruana-creatina.jpg`       |
| Carvão Ativado Vegetal + Beterraba 500 mg   | `assets/products/carvao-beterraba.jpg`            |
| Feno Grego 500 mg                           | `assets/products/feno-grego.jpg`                  |
| Feno Grego + Creatina 500 mg                | `assets/products/feno-grego-creatina.jpg`         |
| Psyllium + Creatina 500 mg                  | `assets/products/psyllium-creatina.jpg`           |
| Maxtesto 500 mg                             | `assets/products/maxtesto.jpg`                    |
| PowerFemme 500 mg                           | `assets/products/powerfemme.jpg`                  |

Enquanto uma imagem não existir, o cartão do produto exibe um espaço reservado tracejado indicando o caminho esperado e o formato (1080×1080). Assim que o arquivo real for adicionado com o nome certo, ele aparece automaticamente — não é preciso editar o HTML.

## Como adicionar novos produtos

No arquivo `catalog.html`, dentro do array `products` (bloco `<script>`), adicione um novo objeto seguindo o mesmo padrão:

```js
{
  image: "assets/products/novo-produto.jpg",
  category: "Categoria",
  name: "Nome do Produto",
  subtitle: "Subtítulo / diferencial",
  composition: "Composição, se for uma fórmula combinada (opcional).",
  description: "Descrição técnica e comercial do produto.",
  contains: "120 cápsulas",
  dose: "500 mg"
}
```

Coloque a foto correspondente (1080×1080 px) em `assets/products/` com o mesmo nome usado em `image`. O layout do cartão (tamanho da imagem, tipografia, espaçamento, marca d'água) é aplicado automaticamente e permanece simétrico entre todos os produtos.

## Catálogo de Terceirização K2 Nutrition

Catálogo de terceirização de suplementos em página única (`catalogo-terceirizacao-k2-nutrition.html`) para a **K2 Nutrition Inteligência em Saúde Ltda** (CNPJ 23.855.514/0001-24).

Reúne todo o portfólio de produtos (linhas Cabelo/Pele/Unhas, Colágeno, Performance e Energia, Saúde e Bem-estar, Imunidade, Ômega 3, Super AZ, Metabolismo, Ossos e Articulações, Linha KIDS e Estimulante), com composição, informação nutricional, opções de cápsula/embalagem e as tabelas de preço por faixa de quantidade — todos os valores já reajustados em +30% sobre a referência original de terceirização. Inclui também os modelos de frascos, potes, latas e tampas disponíveis e a tabela de valor dos rótulos.

Abra o arquivo `catalogo-terceirizacao-k2-nutrition.html` diretamente no navegador para visualizar.
