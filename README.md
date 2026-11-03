# Pikpega — Infantil e Adulto

Site institucional estático com quatro páginas, feito em HTML5 e CSS3 com Bootstrap 5.3.8. Não há JavaScript, carrinho, preços ou fluxo de compra.

## Estrutura

```text
index.html
kids.html
adulto.html
redes.html
css/style.css
manus-routes.json
img/                     # pasta reservada para recursos locais
```

## Visualizar no projeto Manus

Abra a pré-visualização do projeto e navegue pelos links do cabeçalho. O CSS do Bootstrap 5.3.8 e as fontes Nunito/Fredoka são carregados por CDN. Os visuais personalizados gerados para o site são servidos pelas rotas de armazenamento do projeto Manus.

## Abrir localmente

Com Python 3 disponível, na pasta do projeto execute `python3 -m http.server 8000` e abra `http://localhost:8000` no navegador. O site não precisa de compilação nem de dependências Node. Como as imagens ilustrativas são servidas pelo armazenamento Manus, para uma cópia totalmente independente descarregue os cinco visuais finais para `img/` e substitua nos HTML os cinco caminhos `/manus-storage/async-images/...` pelos caminhos locais correspondentes, como `img/hero-brecho.webp`. Também pode substituir as imagens por fotografias autorizadas do brechó.

## Dados que faltam confirmar

Antes de publicar com os contactos ativos, confirme o perfil oficial do Instagram e o respetivo URL, o número de WhatsApp e o link de conversa, bem como o endereço. Os identificadores de Instagram e telefone no site são provisórios. O botão do Maps abre uma pesquisa textual com o endereço informado; confirme o resultado. Os exemplos visuais e os textos nas páginas Kids e Adulto são demonstrativos, não confirmam peças disponíveis, marcas, tamanhos ou condições.

## Publicar em alojamento estático

Copie os quatro HTML, `css/`, `img/` e `manus-routes.json` para a raiz do serviço de alojamento. O documento inicial é `index.html`. Para alojamento fora do Manus, coloque os visuais descarregados em `img/` e atualize os caminhos conforme indicado acima. Reveja os links de contactos, o endereço e os exemplos antes de tornar o site público. O Bootstrap e as fontes externas requerem ligação à Internet; o conteúdo HTML continua a ser carregado sem JavaScript.
