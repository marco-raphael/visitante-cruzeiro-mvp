# ⚓ Cruzeiro Tech & Fun - App de Eventos (MVP)

🔗 **[Testar o Protótipo Online -> https://large-star.surge.sh/]**

<img width="981" height="867" alt="image" src="https://github.com/user-attachments/assets/60216912-be38-4c7e-8f50-f090c4e78553" />

## 🎯 O Desafio (Por que 30 minutos?)
O objetivo deste microprojeto foi validar a viabilidade de uma interface interativa para um trabalho universitário, com foco extremo em agilidade e entrega de valor visual. O cenário simulado exige uma navegação rápida e intuitiva, considerando que os passageiros de um cruzeiro acessariam o app via QR Codes espalhados pelo navio.

Em vez de focar em uma arquitetura complexa, a prioridade foi construir um **MVP (Mínimo Produto Viável)** funcional no menor tempo possível, provando que é viável entregar uma excelente UX sem over-engineering.

## 🛠️ Stack Tecnológica
* **React + Vite:** Para componentização rápida e inicialização instantânea.
* **Tailwind CSS v4:** Escolhido pela velocidade de estilização e facilidade em criar um layout estritamente *Mobile-First*.
* **Mock Data (JSON):** Banco de dados simulado estaticamente para evitar latência e complexidade de backend nesta fase conceitual.
* **Surge:** Para deploy contínuo e instantâneo de arquivos estáticos.
* **Link Surge** https://large-star.surge.sh/

## ✨ Funcionalidades Entregues
* **Interface Mobile-First:** O layout é travado em dimensões de smartphone (`max-w-md`), garantindo a visualização correta mesmo em desktops.
* **Navegação SPA (Single Page Application):** Transições instantâneas entre telas (Agenda e Mapa) sem recarregar a página.
* **Renderização Dinâmica:** Leitura de um arquivo JSON centralizado para gerar a grade de programação e os mapas de deques.

## 🚀 Como rodar localmente

1. Clone o repositório:
\`\`\`bash
git clone https://github.com/SEU-USUARIO/app-visitante-evento.git
\`\`\`

2. Instale as dependências:
\`\`\`bash
npm install
\`\`\`

3. Inicie o servidor de desenvolvimento:
\`\`\`bash
npm run dev
\`\`\`
