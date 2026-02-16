# 🍳 Culinary • Livro de Receitas Inteligente
O Culinary é uma aplicação web progressiva e minimalista para gerenciamento de receitas culinárias. Projetado para ser rápido, acessível e funcional, ele permite que você organize suas criações gastronômicas com facilidade, contando com recursos úteis como timer integrado, modo escuro e sistema de backup.
# ✨ Demonstração e Funcionalidades
   Organização por Categorias: Filtre suas receitas entre Salgados, Doces, Saudáveis e Bebidas.
   Busca Inteligente: Encontre receitas instantaneamente com busca otimizada via debounce.
   Timer Integrado: Cronômetro prático dentro de cada receita para auxiliar no preparo.
   Modo Escuro (Dark Mode): Interface adaptável que respeita a preferência do sistema ou do usuário.
   Favoritos: Salve suas receitas prediletas com um clique.
   Backup (Import/Export): Não perca seus dados. Exporte suas receitas para um arquivo JSON e importe-as em qualquer outro dispositivo.
   Totalmente Responsivo: Experiência otimizada para smartphones, tablets e desktops.
# 🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando tecnologias web puras (Vanilla) para garantir máxima performance e zero dependências pesadas:
   HTML5: Uso de tags semânticas e a nova API <dialog> para modais nativos.
   CSS3: Variáveis nativas (design system), CSS Grid para layouts complexos e animações fluidas.
   JavaScript (ES6+): Manipulação de DOM segura, persistência com localStorage e lógica de timer.
   Font Awesome: Iconografia intuitiva.
   Google Fonts: Tipografia selecionada (Outfit e Playfair Display) para uma leitura agradável.
# 🚀 Como Executar o Projeto
Como o projeto não utiliza frameworks ou bundlers (como React ou Webpack), a execução é extremamente simples:
   Clone o repositório:
   git clone https://github.com/seu-usuario/culinary.git

   Abra o arquivo:
   Basta abrir o arquivo index.html em qualquer navegador moderno.
Dica: Você também pode usar a extensão "Live Server" no VS Code para visualizar as alterações em tempo real.
# Estrutura de Código
Para facilitar a manutenção, o código está dividido em módulos lógicos dentro do script:
   utils: Funções utilitárias para debounce, criação de elementos e sanitização de URLs.
   state: Gerenciamento do estado global (filtros, busca e dados).
   modalManager: Controle de abertura e fechamento dos diálogos nativos.
   app: Núcleo da aplicação (renderização, persistência e listeners).
   timer: Módulo independente para controle de tempo.
# 🔒 Segurança e Performance
   Sanitização: O código evita o uso de innerHTML com dados inseridos pelo usuário para prevenir ataques de XSS.
   Performance de Renderização: Implementado content-visibility: auto no grid de receitas e DocumentFragment para minimizar o reflow do navegador durante a renderização de grandes listas.
   Lazy Loading: Imagens de receitas são carregadas sob demanda para economizar dados e acelerar o carregamento inicial.
# 📄 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
# ✍️ Autor
Desenvolvido com ❤️ por Arthur Wonglon. Se este projeto foi útil para você, considere dar uma ⭐️ no GitHub!
