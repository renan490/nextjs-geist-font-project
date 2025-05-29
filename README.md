# Plataforma de Investimentos

Uma plataforma moderna para negociação de ações e gestão de investimentos desenvolvida com Next.js e Tailwind CSS.

## Estrutura do Projeto

```
/project/sandbox/user-workspace/
├── src/
│   ├── app/
│   │   ├── page.tsx (Página Inicial)
│   │   ├── layout.tsx (Layout Principal)
│   │   ├── portfolio/ (Carteira)
│   │   ├── market/ (Mercado)
│   │   ├── trade/ (Negociar)
│   │   └── account/ (Conta)
│   ├── components/
│   │   └── ui/ (Componentes UI)
│   ├── hooks/
│   └── lib/
├── public/
└── package.json
```

## Requisitos

- Node.js (versão 16 ou superior)
- npm (gerenciador de pacotes do Node.js)

## Como Instalar

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITÓRIO]
```

2. Navegue até o diretório do projeto:
```bash
cd [NOME_DO_DIRETÓRIO]
```

3. Instale as dependências:
```bash
npm install
```

## Como Executar

1. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

2. Abra o navegador e acesse:
```
http://localhost:8000
```

## Páginas Disponíveis

- **Início** (`/`): Visão geral do mercado e notícias
- **Carteira** (`/portfolio`): Visão geral dos investimentos
- **Mercado** (`/market`): Listagem de ações disponíveis
- **Negociar** (`/trade`): Formulário para compra e venda
- **Conta** (`/account`): Configurações e histórico

## Tecnologias Utilizadas

- Next.js
- TypeScript
- Tailwind CSS
- Shadcn UI Components

## Desenvolvimento

O projeto está estruturado de forma modular, com componentes reutilizáveis e páginas organizadas seguindo as melhores práticas do Next.js. A interface está em português brasileiro e utiliza um design moderno em preto e branco.
