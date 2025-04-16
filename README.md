Aura Beauty Dashboard
Bem-vindo ao Aura Beauty Dashboard, um sistema de controle administrativo e visualização de dados da empresa fictícia Aura Beauty. Essa aplicação foi construída com HTML5, Tailwind CSS, JavaScript, Chart.js e componentes modais personalizados.

📁 Estrutura do Projeto
bash
Copiar
Editar
/AuraBeautyDashboard
│
├── index.html                # Página principal do dashboard
├── vendas.html              # Página de visualização de vendas
├── faturamentoanual.html    # Página de controle de produtos
├── filial.html              # Página com informações das filiais
├── Logo_AuraBeauty.png      # Logo da empresa
├── /img                     # Imagens de ícones usadas na sidebar
└── README.md                # Este arquivo
🧭 Navegação e Páginas
🖥️ index.html – Dashboard Principal
Sidebar à esquerda com os ícones de navegação para:

Vendas

Faturamento

Filiais

Header com campo de busca e botão de perfil (abre modal).

Cards principais:

"Acrescentar Produto": botão que abre um modal para cadastrar produtos.

"Produtos Cadastrados": abre uma lista dos produtos salvos em localStorage.

"Dados de São Paulo": estatísticas da filial principal.

Gráfico de Assinaturas: usando Chart.js, exibe dados mensais de performance.

Sidebar direita:

Chat com influenciadores.

Mapa com localização da empresa (Google Maps Embed).

📊 vendas.html – Página de Vendas
Layout similar ao index.html.

Espaço reservado para gráficos, dados comparativos e filtros.

💰 faturamentoanual.html – Cadastro de Produtos
Foi renomeado funcionalmente para permitir o cadastro de produtos.

Modal para adicionar novo produto com campos (nome, categoria, preço).

Produtos são armazenados via localStorage e listados em outro modal.

🏢 filial.html – Informações de Filiais
Estrutura focada em mostrar a localização, status e estatísticas de cada filial da Aura Beauty.

Ideal para análise logística e de distribuição.

🧩 Funcionalidades Implementadas

Funcionalidade	Descrição
🌐 Navegação via sidebar	A sidebar lateral permite acesso rápido às páginas.
📈 Gráfico de assinaturas	Renderizado com Chart.js para dados de performance mensal.
➕ Cadastro de Produto	Modal com formulário simples para inserir produto manualmente.
📋 Listagem de Produtos	Exibe os produtos salvos dinamicamente.
📱 Responsividade Completa	Compatível com celulares, tablets e desktops.
💬 Chat Lateral Simbólico	Simula uma conversa com influenciadores.
🗺️ Mapa das lojas	Embed de mapa da unidade Aura Beauty.
🛠️ Tecnologias Usadas
HTML5 – marcação semântica

Tailwind CSS – estilização moderna e responsiva

JavaScript (puro) – interação, modais e armazenamento local

Chart.js – biblioteca para gráficos

Google Maps Embed – mapa das filiais

📝 Como rodar
Clone ou baixe o repositório.

Abra index.html em seu navegador.

Navegue pelas páginas através da sidebar.

Cadastre produtos e visualize listas sem banco de dados, usando o localStorage do navegador.
