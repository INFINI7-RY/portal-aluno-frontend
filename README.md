# 🧱 Projeto Frontend - Clean Architecture com Next.js, TypeScript e TailwindCSS

Este projeto é o frontend de uma aplicação modular, construído com **Next.js** e **TailwindCSS**, seguindo os princípios da **Clean Architecture**. Ele foi projetado para ser escalável, de fácil manutenção e desacoplado do backend.

## 🚀 Tecnologias Utilizadas

- [Next.js](https://nextjs.org/) 
- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Zod](https://zod.dev/)
- [Jest](https://jestjs.io/)

---

## 📂 Estrutura de Pastas (Clean Architecture Adaptada)

```bash
src/
├── domain/            # Regras de negócio, contratos, entidades puras
├── application/       # Casos de uso (serviços, lógica da aplicação)
├── infrastructure/    # Gateways, Axios, comunicação com APIs externas
├── interfaces/        # Componentes, páginas, formulários, hooks
├── shared/            # Utilitários, tipos comuns, schemas de validação
└── app/               # Rotas e layout base do Next.js (App Router)
```
---

## 🧪 Instalação e Execução
### 🔧 Pré-requisitos
- Node.js (v18 ou superior)
- Yarn (ou npm)
- docker (opcional, se for utilizar junto com backend)

---

### 📦 1. Instale as dependências
```
yarn install
```

### ⚙️ 2. Configure as variáveis de ambiente

Crie um arquivo .env.local na raiz do projeto com o seguinte conteúdo:
```
NEXT_PUBLIC_API_URL=http://localhost:3000
```

### 🏁 3. Execute a aplicação
```
yarn dev
```
