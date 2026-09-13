# Prompt de imagem — Maca Peruana + Creatina 500 mg (120 cápsulas)

Briefing comercial para gerar a foto do produto usada em `assets/products/maca-peruana-creatina.jpg`
(formato final: **1080 × 1080 px**, conforme padrão do catálogo Realmed).

Identidade visual da marca a respeitar: fundo claro/neutro, tons **azul-marinho (#0b1f45 / #123a70)**
e **dourado (#c9a24a)**, estética premium/farmacêutica, elegante e confiável.

> **Fluxo de uso: imagem de referência (image-to-image)**
> Você vai **anexar a foto real do frasco** à IA. O objetivo aqui NÃO é gerar
> um frasco novo do zero — é usar a IA apenas para melhorar cenário,
> iluminação e composição **mantendo o produto original 100% fiel**: mesmo
> rótulo, mesma tipografia, mesma logo, mesmas cores, mesmo formato de
> frasco e tampa. Ferramentas de geração pura a partir de texto (Midjourney
> "text-to-image", por exemplo) tendem a redesenhar o rótulo do zero — por
> isso, para este caso, dê preferência a ferramentas de **edição/composição
> com imagem de referência** (ver seção 5).

---

## 1. Prompt principal (edição com imagem anexada — manter fidelidade total)

Use como instrução de edição junto com a foto anexada (ChatGPT/GPT-4o com
imagem, Leonardo.Ai "Image Guidance", Adobe Firefly, Photoroom, Canva Magic
Studio):

```
Using the attached product photo as the exact reference, keep the bottle,
label, logo, typography, colors, cap and proportions 100% unchanged and
unedited — do not redraw, recreate, or alter any text or design element on
the label. Only enhance the surrounding scene: place the same bottle on a
softly reflective dark navy surface, add scattered beige capsules and fresh
peruvian maca root slices with a light dusting of maca powder around it,
apply dramatic professional studio lighting with a subtle golden rim light
and soft shadows, clean minimal background in a gentle gradient from white
to light gray with soft navy and gold accents, shallow depth of field on
the background while the product itself stays perfectly sharp and
untouched, high-end nutraceutical advertising style, symmetrical centered
composition, square format 1:1, 8k photorealistic commercial packshot, no
people, no added logos or watermarks, preserve original product exactly as
in the attached image
```

**Tradução / adaptação em português:**

```
Usando a foto anexada do produto como referência exata, mantenha o frasco,
rótulo, logotipo, tipografia, cores, tampa e proporções 100% inalterados —
não redesenhe, não recrie e não altere nenhum texto ou elemento do rótulo.
Apenas melhore o cenário ao redor: posicione o mesmo frasco sobre uma
superfície azul-marinho levemente reflexiva, adicione cápsulas bege
espalhadas e fatias de raiz de maca peruana fresca com um leve pó de maca
ao redor, aplique iluminação profissional de estúdio com contraluz dourada
sutil e sombras suaves, fundo minimalista em degradê de branco para cinza
claro com toques em azul-marinho e dourado, profundidade de campo rasa no
fundo mantendo o produto perfeitamente nítido e intocado, estilo de
publicidade nutracêutica premium, composição centralizada e simétrica,
formato quadrado 1:1, fotorrealismo comercial em 8k, sem pessoas, sem
logotipos ou marcas d'água adicionais, preserve o produto original
exatamente como na imagem anexada
```

---

## 2. Prompt alternativo (lifestyle / apelo de desejo — energia e performance)

Mesma lógica: o frasco anexado entra **sem alterações**, só o ambiente muda
para reforçar o benefício (energia + força):

```
Using the attached product photo as the exact reference, keep the bottle
label, logo, text, colors and shape completely unchanged. Composite this
exact same bottle into a powerful lifestyle scene: dynamic splash of golden
light particles and subtle energy motion blur in the background, scattered
capsules catching dramatic side light, faint blurred silhouette of an
athletic figure mid-motion in the dark navy background suggesting strength
and vitality, cinematic contrast, gold and deep navy blue color grading,
high-end supplement advertising mood, sense of power and desire, square 1:1
composition, product stays ultra sharp and unedited while background is
stylized, 8k photorealistic, no added logos or text
```

---

## 3. Prompt negativo (evitar erros comuns de IA)

```
redrawn label, altered text, changed logo, different typography, changed
bottle shape or color, misspelled text, blurry or distorted label,
duplicated bottle, extra deformed capsules, deformed hands, extra fingers,
cartoonish, low resolution, oversaturated, cluttered background, added
watermark, generic fake brand, plastic toy look, unrealistic lighting
```

---

## 4. Checklist antes de anexar a foto

- Envie a foto do frasco em **alta resolução**, bem iluminada, sem reflexos
  fortes nem sombras duras cobrindo o rótulo — quanto mais nítido o
  original, mais fiel fica o resultado.
- Reforce sempre, no texto do pedido à IA, que **rótulo, logo e texto não
  podem ser redesenhados** — algumas ferramentas ignoram isso se não for
  dito explicitamente (e repetido) no prompt.
- Depois de gerar, **confira o rótulo de perto**: se a IA alterar qualquer
  letra, número ou cor, gere novamente ou peça correção pontual só naquela
  área (inpainting), em vez de aceitar o resultado.

---

## 5. Ferramentas recomendadas para este fluxo (fidelidade ao produto)

Priorize ferramentas de **edição/composição com imagem**, não geração pura
por texto:

| Ferramenta | Como usar |
|---|---|
| **ChatGPT (GPT-4o / GPT-Image)** | Anexe a foto + cole o prompt da seção 1 pedindo para "editar apenas o fundo, mantendo o produto idêntico" |
| **Adobe Firefly — Generative Fill/Expand** | Recorte o produto e use "preenchimento generativo" só no fundo — o produto original nunca é tocado |
| **Photoroom (IA de fundo)** | Remove o fundo automaticamente e gera um novo cenário atrás do produto, mantendo o recorte 100% original |
| **Canva Magic Studio** | "Remover fundo" + "Editor Mágico" para gerar cenário novo em volta do recorte do produto |
| **Leonardo.Ai — Image Guidance** | Use a foto como referência com peso alto de fidelidade (Image Guidance perto do máximo) |

> Dica prática: o caminho mais seguro e com **zero risco de alterar o
> rótulo** é recortar o produto (remover fundo) e gerar/editar **apenas o
> cenário atrás dele** — em vez de pedir para a IA "reconstruir" a cena
> inteira com o frasco incluído.

---

## 6. Observações finais

- Exporte o resultado final em **1080 × 1080 px**, fundo neutro, e salve como
  `assets/products/maca-peruana-creatina.jpg` — o catálogo (`catalog.html`)
  já está preparado para exibi-lo automaticamente assim que o arquivo existir.
- Para manter consistência visual entre todos os produtos da linha (Maca
  Peruana, Maca Negra, Feno Grego + Creatina, Psyllium + Creatina etc.),
  reutilize o mesmo prompt-base (seção 1) trocando apenas os ingredientes
  visuais de apoio (raiz/pó em destaque) e a foto anexada de cada produto,
  gerando todas na mesma sessão/estilo para não perder a padronização.
