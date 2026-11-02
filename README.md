# ⚖️ Lord Perrout Advocacia

**Site Institucional Jurídico | Next.js • React • TypeScript • Tailwind CSS**

<p align="center">
  <strong>Direito com presença para decisões importantes.</strong>
</p>

<p align="center">
  <a href="https://lord-perrout-advocacia.vercel.app/" target="_blank">🌐 Acessar projeto online</a>
</p>

---

## 📌 Sobre o projeto

O **Lord Perrout Advocacia** é um projeto de desenvolvimento web voltado à criação de uma presença digital institucional para um escritório de advocacia.

A plataforma foi concebida para apresentar a identidade do escritório, comunicar sua proposta de atuação, divulgar especialidades jurídicas, apresentar os profissionais da equipe e facilitar o contato com potenciais clientes.

O projeto combina uma interface moderna, navegação intuitiva, identidade visual sofisticada e recursos interativos, priorizando uma experiência de utilização consistente em computadores, tablets e dispositivos móveis.

A proposta é transformar a presença digital do escritório em um canal institucional de apresentação, comunicação e relacionamento com o público.

## 🎯 Objetivos do projeto

- Desenvolver uma presença digital profissional para o escritório.
- Apresentar a identidade institucional e os diferenciais da advocacia.
- Organizar e divulgar as principais áreas de atuação jurídica.
- Disponibilizar informações sobre os profissionais da equipe.
- Publicar conteúdos informativos relacionados ao universo jurídico.
- Facilitar o contato por meio de formulários e acesso ao WhatsApp.
- Oferecer navegação responsiva e uma experiência visual consistente.
- Estabelecer uma base técnica organizada para futuras evoluções.

## ✨ Funcionalidades implementadas

### 🏠 Página inicial

- Apresentação institucional do escritório.
- Seção principal com proposta de valor e chamadas para ação.
- Áreas jurídicas em formato interativo.
- Apresentação dos diferenciais do escritório.
- Seção sobre metodologia de atendimento.
- Chamadas para agendamento de conversas.
- Elementos visuais e animações.

### 🏛️ Áreas de atuação

Apresentação de diferentes especialidades jurídicas, incluindo:

- Direito Civil.
- Direito Trabalhista.
- Direito Empresarial.
- Direito Previdenciário.
- Direito Penal.
- Direito Militar.
- Direito do Consumidor.
- Direito Imobiliário.
- Direito Tributário.
- Direito Contratual.

O projeto também apresenta páginas específicas de detalhamento para algumas especialidades, com serviços, informações sobre a atuação e chamadas para contato.

### 👥 Equipe profissional

- Apresentação dos profissionais.
- Perfis individuais.
- Informações biográficas e profissionais.
- Especialidades e áreas de atuação.
- Recursos interativos para expansão dos perfis.

### 📰 Blog e conteúdo jurídico

- Listagem de artigos.
- Organização por categorias.
- Pesquisa de conteúdo.
- Filtragem por categoria.
- Apresentação de artigos individuais.
- Identificação de autor, data e tempo estimado de leitura.
- Sugestões de conteúdos relacionados.

### 📩 Contato

- Formulário com campos para identificação e descrição da solicitação.
- Validação de informações no navegador.
- Seleção de área jurídica.
- Interface de confirmação visual após o preenchimento.

**Observação técnica:** o envio do formulário está implementado como uma simulação no front-end. Uma integração com serviço de e-mail, API ou backend poderá ser desenvolvida em uma etapa futura.

### 💬 Integração visual com WhatsApp

- Botão flutuante de acesso rápido.
- Exibição de mensagem de apresentação.
- Abertura de conversa pelo WhatsApp.
- Mensagem inicial preenchida automaticamente.

### 🔐 Páginas institucionais e legais

- Política de Privacidade.
- Termos de Uso.
- Informações institucionais sobre tratamento de dados e utilização do site.

## 🎨 Identidade visual e experiência do usuário

O projeto utiliza uma identidade visual sofisticada, construída para transmitir profissionalismo, credibilidade e elegância.

Características visuais:

- Azul-marinho como cor institucional predominante.
- Dourado como elemento de destaque.
- Tons claros e neutros para equilíbrio visual.
- Tipografia Inter para textos e elementos funcionais.
- Tipografia Playfair Display para títulos e elementos editoriais.
- Composição visual com espaçamento amplo.
- Cards, elementos interativos e transições.
- Layout adaptável a diferentes tamanhos de tela.

A interface foi desenvolvida considerando princípios de UI (User Interface) e UX (User Experience), buscando proporcionar clareza na apresentação das informações e facilidade de navegação.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| Next.js 16 | Framework principal |
| React 19 | Construção da interface |
| TypeScript | Tipagem e organização do código |
| Tailwind CSS 4 | Estilização |
| Radix UI | Componentes acessíveis |
| Lucide React | Ícones |
| React Hook Form | Recursos de gerenciamento de formulários |
| Zod | Validação de dados |
| Recharts | Recursos de visualização de dados |
| Vercel Analytics | Análise de utilização do site |
| Next Themes | Gerenciamento de temas |

## 🏗️ Arquitetura e organização

O projeto utiliza a estrutura de diretórios do **Next.js App Router**, com separação entre páginas, componentes reutilizáveis, recursos visuais, estilos e funções auxiliares.

```text
Lord-Perrout-Advocacia/
│
├── app/
│   ├── areas/
│   │   ├── civil/
│   │   ├── empresarial/
│   │   ├── trabalhista/
│   │   └── previdenciario/
│   │
│   ├── blog/
│   │   └── [slug]/
│   │
│   ├── contato/
│   ├── equipe/
│   ├── privacidade/
│   ├── sobre/
│   ├── termos/
│   │
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   ├── ui/
│   ├── animated-section.tsx
│   ├── counter.tsx
│   ├── footer.tsx
│   ├── header.tsx
│   ├── home-experience.tsx
│   ├── theme-provider.tsx
│   └── whatsapp-button.tsx
│
├── hooks/
│   ├── use-intersection-observer.ts
│   ├── use-mobile.ts
│   └── use-toast.ts
│
├── lib/
│   └── utils.ts
│
├── public/
│   └── images/
│
├── styles/
│   └── globals.css
│
├── next.config.mjs
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── postcss.config.mjs
├── tsconfig.json
└── eslint.config.mjs
```

## ⚙️ Instalação e execução local

### Pré-requisitos

- Node.js.
- pnpm.
- Git.

### 1. Clonar o repositório

```bash
git clone https://github.com/RodrigoElias-Mello/Lord-Perrout-Advocacia.git
```

### 2. Entrar na pasta do projeto

```bash
cd Lord-Perrout-Advocacia
```

### 3. Instalar as dependências

```bash
pnpm install
```

### 4. Executar em ambiente de desenvolvimento

```bash
pnpm dev
```

### 5. Acessar no navegador

```text
http://localhost:3000
```

## 📦 Scripts disponíveis

| Comando | Descrição |
|---|---|
| `pnpm dev` | Executa o ambiente de desenvolvimento |
| `pnpm build` | Gera a versão de produção |
| `pnpm start` | Inicia a aplicação em produção |
| `pnpm lint` | Executa a análise estática com ESLint |

## 🚀 Publicação

O projeto está disponível online por meio da plataforma Vercel.

**Endereço de produção:**

https://lord-perrout-advocacia.vercel.app/

A estrutura utiliza recursos do ecossistema Next.js e pode ser integrada ao fluxo de implantação contínua da Vercel.

## 🔍 Possibilidades de evolução

A arquitetura atual permite planejar novas funcionalidades, como:

- Integração real do formulário de contato com backend.
- Envio automático de solicitações por e-mail.
- Implementação de um CMS para gerenciamento de artigos.
- Cadastro e gerenciamento de conteúdos sem alterações diretas no código.
- Integração de newsletter com serviço especializado.
- Painel administrativo.
- Gerenciamento dinâmico de profissionais e especialidades.
- Integração com banco de dados.
- Melhorias de SEO e desempenho.
- Ampliação das páginas individuais das áreas jurídicas.

Esses recursos representam possibilidades de evolução e não devem ser confundidos com funcionalidades já implementadas.

## 👨‍💻 Desenvolvimento

**Desenvolvido por Rodrigo Elias Alfama de Mello**

Desenvolvedor Web | Front-End | Soluções Digitais

Formação: Análise e Desenvolvimento de Sistemas.

O desenvolvimento envolveu estruturação de páginas, organização de componentes, implementação de interfaces responsivas, aplicação de identidade visual, recursos interativos e configuração do ambiente de desenvolvimento.

### Contato profissional

- **Portfólio:** https://portifolio-rodrigo-elias.vercel.app
- **LinkedIn:** https://www.linkedin.com/in/rodrigoelias1709
- **GitHub:** https://github.com/RodrigoElias-Mello
- **WhatsApp:** https://wa.me/5521989899240

---

<p align="center">
  Desenvolvido com dedicação, tecnologia e atenção aos detalhes.
</p>

<p align="center">
  © Lord Perrout Advocacia — Projeto institucional.
</p>
