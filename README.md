# SyntaxWear

Site estático de e-commerce de tênis e sneakers.

## Sobre

Este projeto é uma landing page de uma loja de sneakers chamada **SyntaxWear**. Ele inclui:
- Uma seção de navegação fixa com menu responsivo.
- Um hero visual chamativo.
- Cards de categorias de tênis.
- Uma grade de produtos em destaque.
- Rodapé com newsletter e links de navegação.

## Tecnologias

- HTML5
- CSS3
- CSS organizados em:
  - `css/reset.css`
  - `css/variables.css`
  - `css/base.css`
  - `css/layout.css`
  - `css/components/*.css`

## Estrutura de pastas

```
/                    - arquivo principal HTML
/css/                - estilos globais e layout
/css/reset.css       - reset de estilos
/css/variables.css   - variáveis css e fontes
/css/base.css        - tipografia e botões
/css/layout.css      - layout global e responsivo
/css/components/     - estilos dos blocos do site
/images/             - imagens usadas no site
/images/banners/     - banners e hero images
/images/icons/       - ícones SVG
/images/logo/        - logotipo
/images/products/    - imagens de produtos e cards
```

## Arquivos principais

- `index.html` - página única do site.
- `css/reset.css` - reset de estilo base.
- `css/variables.css` - declaração de fontes e variáveis.
- `css/base.css` - estilos base e botões.
- `css/layout.css` - regras de layout geral da página.
- `css/components/header.css` - estilos do cabeçalho.
- `css/components/hero.css` - estilos da seção hero.
- `css/components/product-category.css` - estilos das categorias.
- `css/components/product-grid.css` - estilos da grade de produtos.
- `css/components/footer.css` - estilos do rodapé.

## Componentes do site

### Cabeçalho
- `header` fixo no topo.
- Menu responsivo com ícones de usuário, ajuda e carrinho.
- Botão hambúrguer aparece em telas menores.

### Hero
- Background com imagem de destaque.
- Chamadas para ação (`Ver modelos` e `Comprar`).
- Título centralizado e estilo moderno.

### Categorias
- Quatro cards com categorias: Casual, Esporte, Moderno, Futurista.
- Cada card usa imagem de produto como background.

### Grade de produtos
- Grid CSS com 6 cards.
- Card principal em destaque (`Krypton One`).
- Cards de produto com imagens de produto e posicionamento em grid.

### Rodapé
- Formulário de newsletter.
- Links de navegação por categorias.
- Links de redes sociais.

## Como usar

1. Abra `index.html` diretamente no navegador.
2. Ou sirva localmente com um servidor estático para melhores resultados.

### Servir localmente (opcional)

No terminal, execute um servidor rápido no diretório do projeto. Por exemplo, com Python:

```bash
cd "c:/Users/lionp/Downloads/Dev Em Dobro/devquest2.0/ecommerce-syntaxwear"
python -m http.server 8000
```

Depois abra no navegador:

```text
http://localhost:8000
```

## Observações

- O site é um protótipo estático e não possui backend.
- Imagens e ícones são carregados localmente via pasta `images`.
- Ajustes de responsividade podem ser feitos em `css/layout.css` e nos componentes.

## Próximas melhorias

- Validar e otimizar acessibilidade.
- Adicionar animações suaves.
- Tornar o menu mobile mais fluido.
- Implementar formulário real de newsletter.
