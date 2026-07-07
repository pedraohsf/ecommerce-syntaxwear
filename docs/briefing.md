# 🛒 Projeto SyntaxWear_

Bem-vindo ao **SyntaxWear**! Esta é a sua loja virtual (e-commerce) focada em vestuário e acessórios para desenvolvedores de software. Aqui você vai encontrar ideias engraçadas de código, referências nerds e muito estilo para a comunidade tech.

---

## 📂 Como a Estrutura de Pastas Funciona

Organizamos seu projeto utilizando boas práticas de desenvolvimento web. Veja o que vai em cada lugar:

### 1. `index.html` (Na raiz do projeto)
É o ponto de entrada principal do seu site (a página inicial / homepage). Nela, estruturamos o conteúdo em HTML5 e vinculamos todos os nossos arquivos de estilo.

### 2. `/css/`
Aqui fica toda a estilização visual do seu site, dividida estrategicamente para não virar bagunça:
*   `base.css`: Guarda as configurações globais do seu site, como o reset de margens, tipografia global, botões e as **variáveis CSS** (onde definimos cores e fontes do projeto de forma centralizada).
*   `layout.css`: Contém a estrutura de alinhamento e posicionamento do site (como containers, flexbox, grades CSS e espaçamento entre seções).
*   `css/components/`: Uma pasta especial para separar cada bloco visual do site. Desse modo, o código fica modular e fácil de dar manutenção:
    *   `header.css`: Estilo da barra de navegação superior.
    *   `panel.css`: Painel de recados ou ofertas do topo.
    *   `hero.css`: Banner principal de destaque.
    *   `product-card.css`: Estilo de cada "cartão" de produto individual.
    *   `product-grid.css`: A grade responsiva que organiza os cartões de produto na tela.
    *   `newsletter.css`: Caixa de inscrição para receber novidades por e-mail.
    *   `footer.css`: O rodapé inferior do site.

### 3. `/images/`
Guarda todas as imagens e fotos do seu e-commerce, divididas por categorias para você se localizar rapidamente:
*   `/logo/`: O logotipo da SyntaxWear.
*   `/banners/`: Banners para o topo (Hero) ou anúncios promocionais.
*   `/products/`: Fotos reais das camisetas, moletons e canecas.

### 4. `/icons/`
Espaço reservado para arquivos de ícones (de preferência no formato `.svg`), como carrinhos de compra, lupas de busca, ícones de redes sociais, etc.

### 5. `/fonts/`
Se você decidir usar fontes salvas localmente (em vez de importá-las pelo Google Fonts via link), coloque os arquivos de fontes (`.woff`, `.woff2`) aqui.

### 6. `/favicons/`
Guarda os ícones de aba do navegador (`favicon.ico` e variações), garantindo que seu site exiba uma logo bonita na aba do usuário.

### 7. `/docs/`
Pasta dedicada à documentação. Você pode usar este arquivo `briefing.md` para anotar ideias de produtos, metas, guias de conteúdo e anotações pessoais do seu aprendizado!

---

## 🚀 Próximos Passos Sugeridos para Você

1.  **Abra o arquivo `index.html`** no seu navegador (usando uma extensão como o *Live Server* do VS Code) para ver a estrutura inicial funcionando com estilo!
2.  **Explore o arquivo `css/base.css`** para entender como as variáveis de cores (`--color-primary`, `--color-dark`, etc.) funcionam. Você pode experimentar mudar os códigos de cores lá para ver a mágica acontecer em todo o site de uma vez só!
3.  **Adicione imagens** nas pastas adequadas e mude os placeholders de imagem no HTML para usar imagens reais!

Desejamos muito sucesso na sua jornada de aprendizado! Codar é uma arte, e agora seu projeto está com uma organização digna de um dev profissional! 💻🔥
