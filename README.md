# CT VOZ - Portal de Instrutores

Aplicação web para apoiar a organização de uma academia de Jiu-Jitsu, centralizando **planejamento de aulas**, **escala de instrutores**, **avisos internos** e **controle de acesso**.

O projeto nasceu de uma necessidade real de reduzir a dependência de planilhas e facilitar o uso pelo celular durante a rotina da equipe.

## Tecnologias


- JavaScript
- HTML5
- CSS3

## Vibe Coding
```Vibe Coding
- React
- Vite
- Supabase Auth
- Supabase Database
- Git
- PWA (Progressive Web App)
```
## Funcionalidades

- Autenticação de usuários
- Perfis de administrador e instrutor
- Controle de permissões por perfil
- Planejamento técnico de aulas
- Escala semanal de instrutores
- Integração entre escala e planejamento
- Gestão de usuários pelo administrador
- Interface responsiva
- Instalação como PWA
- Atualização de dados do Supabase em tempo real onde aplicável

## Objetivo do projeto

Criar uma aplicação simples e acessível para substituir controles dispersos em planilhas e facilitar o planejamento semanal dos professores do CT VOZ.

Além da implementação da interface, o desenvolvimento envolve modelagem das funcionalidades, autenticação, integração com banco de dados, controle de permissões, tratamento de erros, manutenção e versionamento com Git.

## Como executar localmente

### Pré-requisitos

- Node.js LTS
- npm
- Projeto no Supabase

### Instalação

```bash
npm install
```

Copie o arquivo de exemplo:

```bash
cp .env.example .env
```

No Windows, você também pode criar manualmente um arquivo `.env` na raiz do projeto.

Preencha as variáveis:

```env
VITE_SUPABASE_URL=https://SEU-PROJETO.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=SUA_CHAVE_PUBLICAVEL
```

Execute o projeto:

```bash
npm run dev
```

Para gerar o build de produção:

```bash
npm run build
```

## Estrutura principal

```text
src/
├── components/     # Componentes reutilizáveis
├── context/        # Contexto de autenticação
├── data/           # Dados de demonstração
├── lib/            # Configuração de serviços externos
├── pages/          # Telas da aplicação
└── styles/         # Estilos globais
```

## Segurança

Credenciais e configurações locais não são versionadas. O projeto utiliza variáveis de ambiente e mantém somente `.env.example` no repositório.

> A chave utilizada no front-end deve ser apenas a chave publicável do Supabase. Regras de acesso aos dados devem ser protegidas por políticas de Row Level Security (RLS) no banco.

## Status

Projeto em desenvolvimento ativo. A versão atual contempla o fluxo principal de autenticação, escala, planejamento e administração de usuários.

## Autor

**Luiz Paulo Pereira**  
Desenvolvimento de Software / Análise e Desenvolvimento de Sistemas  
LinkedIn: https://www.linkedin.com/in/luizppaulo/
