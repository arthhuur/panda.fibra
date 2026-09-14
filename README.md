# 🐼 Panda Fibra & Network — Landing Page & Simulador B2B/B2C

Uma landing page moderna, intuitiva e 100% responsiva para a **Panda Fibra & Network**, provedor de internet fibra óptica e soluções de redes corporativas. O projeto combina ofertas de planos residenciais (B2C) com um construtor de propostas interativo em tempo real para soluções empresariais (B2B).

🔗 **Acesse o projeto online:** [arthhuur.github.io/panda.fibra](https://arthhuur.github.io/panda.fibra/)

---

## 🚀 Funcionalidades do Projeto

### 🏡 Módulo Residencial (B2C)
* **Verificador de Cobertura:** Consulta interativa por CEP com feedback visual de disponibilidade nas regiões de cobertura (ABC Paulista).
* **Oferta em Destaque:** Card promocional com contador regressivo de oferta por tempo limitado.
* **Catálogo de Planos:** Apresentação clara de velocidades, vantagens e chamadas diretas para contratação.

### 🏢 Simulador Empresarial Interativo (B2B)
* **Interactive Quote Builder (4 Etapas):**
  1. **Escolha de Banda:** Seleção flexível de velocidade (100 a 1000 Mbps).
  2. **Recursos de Rede:** Adicionais como IP Fixo dedicado, SLA garantido em até 4h, Wi-Fi 6 Mesh gerenciado, telefonia VoIP e Link de Backup redundante.
  3. **Condições Contratuais:** Descontos progressivos de acordo com a fidelidade escolhida (sem fidelidade, 12 ou 24 meses).
  4. **Resumo e Checkout:** Cálculo dinâmico do valor mensal total e botão direto para **geração de proposta via WhatsApp**.

### 🛠️ Recursos Gerais & UX
* **Redirecionamento Inteligente via WhatsApp:** Mensagens pré-formatadas contendo todos os detalhes do plano ou da cotação B2B montada pelo cliente.
* **Buscador de Plano Ideal:** Ferramenta interativa de seleção com base no perfil de uso do usuário (Home Office, Streaming/Jogos, PMEs ou Corporativo).
* **Seção de Vantagens e Dúvidas Frequentes (FAQ):** Accordion interativo para sanar dúvidas comuns sobre instalação e contratação.
* **Design 100% Responsivo:** Layout adaptável para smartphones, tablets e desktops, incluindo menu mobile interativo (drawer).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível.
* **Tailwind CSS (via CDN):** Estilização moderna e utilitária, garantindo responsividade total sem necessidade de pré-processadores externos.
* **JavaScript (ES6+):** Lógica dinâmica para transição entre abas B2C/B2B, cálculo de valores em tempo real no simulador e navegação fluida.
* **Lucide Icons:** Biblioteca de ícones vetoriais leve e moderna.
* **Inter Font:** Tipografia limpa para excelente legibilidade.

---

## 📚 O que foi aprendido neste projeto?

Durante o desenvolvimento deste projeto, foram consolidados e aplicados diversos conceitos práticos de desenvolvimento web e arquitetura de redes/TI:

1. **Arquitetura e Segmentação B2B vs. B2C:** Como planejar a experiência do usuário (UX/UI) para atender tanto ao cliente consumidor final quanto a clientes corporativos com necessidades avançadas.
2. **Desenvolvimento Responsivo Mobile-First:** Uso avançado do grid e flexbox do Tailwind CSS para adaptar layouts complexos (como tabelas e simuladores) para telas de celulares.
3. **Manipulação Avançada de DOM com JavaScript:**
   - Criação de fluxos em etapas (Wizards/Steppers) sem recarregar a página.
   - Cálculo e atualização dinâmica de preços com base em múltiplos parâmetros (banda + adicionais + desconto de contrato).
   - Formatação e codificação de URLs (`encodeURIComponent`) para integração direta com a API do WhatsApp.
4. **Conceitos do Setor de Telecomunicações & Redes:** Incorporação de termos e serviços reais do mercado de ISP e infraestrutura, tais como SLA de atendimento, IP Fixo dedicado, Wi-Fi 6 Mesh, redes GPON/FTTH e redundância de link.
5. **Hospedagem e CI/CD Simples:** Publicação, versionamento e gerenciamento de ativos usando o **GitHub** e o **GitHub Pages**.

---

## 📂 Como executar o projeto localmente

Não é necessário instalar dependências ou configurar ambientes de compilação!

1. Clone o repositório:
```bash
git clone [https://github.com/arthhuur/panda.fibra.git](https://github.com/arthhuur/panda.fibra.git)

Abra a pasta do projeto.

Clique duas vezes no arquivo index.html para abri-lo em qualquer navegador.

Desenvolvido por Arthur Lisboa 🚀
