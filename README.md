# 💡 Planej.ai – Educador Financeiro Inteligente & Acolhimento Mental

O **Planej.ai** é uma aplicação web de planejamento financeiro pessoal com um grande diferencial: ele une **saúde financeira e saúde mental**. Entendendo que falar de dinheiro gera ansiedade e estresse, o sistema substitui tabelas complexas por uma abordagem clara, amigável e acolhedora, focando no consumo consciente e na inteligência emocional.

---

## 🚀 O que o projeto faz?

O projeto funciona diretamente no navegador e simula a experiência de um assistente financeiro que atua como aquele amigo que entende de dinheiro: ele não julga, fala de forma simples e dá o empurrãozinho que falta para o orçamento fechar no azul.

### 📊 Funcionalidades do MVP (Estrutura do Front-end):
*   **Regra dos Três Baldes:** Substitui dezenas de categorias por três divisões visuais simples:
    *   **Essencial (50%):** Aluguel, contas, mercado.
    *   **Estilo de Vida (30%):** Lazer, iFood, assinaturas.
    *   **Futuro (20%):** Reserva de emergência ou pagamento de dívidas.
*   **Simulador de Metas Interativo:** Um slider (*Drag and Drop*) onde o usuário arrasta a barra para ver o tempo necessário para atingir seu objetivo mudar em tempo real (ex: de 2 anos para 6 meses), tornando a meta palpável sem termos técnicos.
*   **Faux-Chatbot (Interface de Chat Simulado):** Uma seção na tela que simula uma conversa de WhatsApp com a IA através de botões de resposta rápida (ex: *"Tô sem grana"*, *"Quero poupar R$ 100"*).

---

## ✨ Nossos Diferenciais: Foco na Saúde Mental

Para evitar que o usuário perca a noção do valor do dinheiro ou sinta ansiedade ao gerenciar suas finanças, adicionamos recursos exclusivos focados em comportamento:

1.  **O "Botão do Impulso" (SOS Compras):** Um botão de destaque para conter compras impulsivas na internet. A IA faz três perguntas reflexivas (*"Isso é necessidade ou desejo?"*, *"Tem o dinheiro ou vai parcelar?"*, *"Se esperar 24h, sua vida muda?"*) e ativa um cronômetro de 24 horas para o usuário pensar antes de liberar o registro.
2.  **Conversor de Preço em "Horas de Trabalho":** O app calcula o valor da hora limpa do usuário com base no seu salário e exibe o custo real dos produtos em esforço físico (ex: *"Essa blusa vai custar 10 horas do seu trabalho. Vale a pena passar dois dias inteiros trabalhando por ela?"*).
3.  **Botão "Pausa para Respirar" (Mindful Breathing):** Uma bolinha interativa na tela que expande e contrai usando animações CSS (`@keyframes`). O app guia o usuário: *"Inspire enquanto a bola cresce... Expire enquanto ela diminui"*, acalmando os batimentos cardíacos nos momentos de tensão financeira.
4.  **Pop-up Anticulpa:** Modais e notificações suaves (*toasts*) que aparecem com frases motivacionais focadas em inteligência emocional caso o usuário passe muito tempo na tela de saldo negativo.
5.  **Filtro "Modo Acolhedor" no Chatbot:** Muda a lógica das respostas da IA para mensagens com dados de conforto emocional (ex: *"Você sabia que mais de 70% das pessoas passam por isso? Você não está sozinho"*).

---

## 📸 Protótipo e Ideia em Desenvolvimento

*(Substitua os links abaixo pelas imagens do seu projeto ou use os prints da sua ideia)*

| Conceito do Projeto | Recursos Extras | Componentes de Mindful |
| :---: | :---: | :---: |
| ![Conceito](https://via.placeholder.com/300x200?text=Os+Tres+Baldes) | ![Recursos](https://via.placeholder.com/300x200?text=Botao+do+Impulso) | ![Mental](https://via.placeholder.com/300x200?text=Pausa+para+Respirar) |

---

## 🛠️ Quais tecnologias foram usadas?

*   **React** (com TypeScript)
*   **Vite** (para inicialização rápida do ambiente)
*   **Tailwind CSS** (para estilização fluida e Modo Escuro)
*   **Lucide React** (para os ícones da interface)

---

## ⚙️ Como executar a aplicação?

1. Clone o repositório ou faça o download:
   ```bash
   git clone [https://github.com/SEU_USUARIO/planejai.git](https://github.com/SEU_USUARIO/planejai.git)

#### 2- Instale as dependências usando o pnpm (ou gerenciador de sua preferência):

pnpm install

#### 3- Inicie o servidor de desenvolvimento local:

pnpm install

#### 4- Abra o endereço indicado no terminal (geralmente http://localhost:5173) no seu navegador.

*🧪 Como testar o fluxo principal?

Na tela inicial, utilize o formulário de simulação multi-etapas para informar a renda e os objetivos.

Navegue até a página de resultados e interaja com o Slider de Metas para ver o tempo se ajustando automaticamente.

Abra o Faux-Chatbot no canto da tela e clique em "Preciso de um conselho amigo hoje" para ativar o Modo Acolhedor.

Clique no componente "Pausa para Respirar" e acompanhe a animação visual de relaxamento por 1 minuto.

*🧠 O que eu aprendi durante o desafio?

Como estruturar um formulário complexo por etapas (Multi-step) utilizando gerenciamento de estados no React.

A importância de criar interfaces focadas na experiência do usuário (UX/UI) que tratem de assuntos sensíveis (como finanças) com empatia e inteligência emocional.

Criação de animações fluidas com CSS puro (@keyframes) para componentes interativos de bem-estar.

Uso prático do localStorage para persistência dos dados de simulação no navegador.

🔮 Evolução Futura: Em próximas versões, o chatbot simulado e as pílulas de conhecimento do SOS Compras serão conectados dinamicamente de forma real à API do Google Gemini, gerando diagnósticos automatizados ainda mais personalizados.
