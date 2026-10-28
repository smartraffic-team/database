# SmartTraffic — Website

## Descrição

Site de apresentação do **SmartTraffic**, uma proposta de controle inteligente de trânsito com visão computacional e IA, priorizando pessoas com mobilidade reduzida. Desenvolvido com React, TypeScript, Vite e Tailwind CSS. Atualmente, este repositório contém apenas o frontend de apresentação.


## Tecnologias

| Camada      | Tecnologias              |
|-------------|--------------------------|
| Frontend    | React, TypeScript, Vite  |
| Estilização | Tailwind CSS             |
| Ambiente    | Node.js 24, npm          |

## Funcionalidades

- Página de apresentação do projeto SmartTraffic
- Explicação da abordagem com visão computacional e IA
- Site institucional

## Estrutura do Repositório

```
smartraffic-web/
├── imgs/             -> Imagens utilizadas no website
├── src/              -> Código-fonte React + TypeScript
├── public/           -> Assets estáticos
├── index.html        -> Entrada do Vite
├── package.json      -> Dependências e scripts
├── vite.config.ts    -> Configuração do Vite
├── tailwind.config.* -> Configuração do Tailwind CSS
└── tsconfig.json     -> Configuração do TypeScript
```

## Fluxograma

```mermaid
flowchart TD
    Homepage[Homepage]
    Homepage --> Início[Início]
    Homepage --> Projeto[df]
    Homepage --> Documentação

    Início --> Funcionamento
    Início --> Tecnologia[Tecnologia Aplicada]
    Início --> UX[Identidade Visual]
    Início --> Mockup[Mockup]
    Início --> Equipe[Equipe]

    Projeto --> Escopo[Escopo Atual]

    Documentação --> Fluxo[Fluxo Atual]
    Documentação --> Componentes
    Documentação --> Resultado
```

## Como rodar

Com **Node.js 24** e **npm** instalados, execute na pasta do repositório:

```bash
npm ci
npm run dev
```

Acesse o endereço exibido no terminal, normalmente `http://localhost:5173`.

Para encerrar, pressione `Ctrl + C`.
