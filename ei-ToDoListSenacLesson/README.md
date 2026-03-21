# 📁 Projeto Freelance — Validação de Produto (To Do List)

## Contexto Profissional

Você foi contratado como **desenvolvedor freelance** para atuar na validação inicial de um produto digital.

O cliente deseja testar a seguinte hipótese:

> *Usuários precisam de uma solução simples, rápida e eficiente para gerenciamento de tarefas.*

Para isso, será desenvolvido um **MVP (Minimum Viable Product)** no formato de uma aplicação **To Do List**.

Este projeto será conduzido como um **ambiente profissional simulado**, com práticas reais de desenvolvimento, versionamento e colaboração.

---

## 📚 Documentação do Projeto

Toda a base de planejamento e execução do projeto está centralizada na pasta:

```plaintext
/specification/
```

### Documentos obrigatórios:

* 📘 `specification/ui-specification.md`
  Contém a especificação completa da interface (layout, componentes, estilos, estados e interações).

* 🧭 `specification/development.md`
  Contém o plano de desenvolvimento faseado, com etapas e organização do trabalho.

📌 **Importante:**
Você deve consultar esses documentos durante todo o desenvolvimento. Eles fazem parte da avaliação.

---

## Roadmap do Projeto

### 🔹 Fase 1 — Estruturação e Front-end (ATUAL)

* Criação do repositório
* Definição da arquitetura
* Implementação do front-end base (junto com o professor)
* Documentação inicial
* Commits semânticos
* Organização profissional do projeto

### 🔹 Fase 2 — Backend e Persistência

* PHP puro (sem frameworks)
* MySQL
* API básica
* Persistência de dados

---

## Sobre o Backend

O backend será desenvolvido futuramente utilizando:

* **PHP puro (Vanilla PHP)**
* Sem frameworks como Laravel

📌 Objetivo:

* Entender a base do backend
* Trabalhar com requisições HTTP
* Manipular dados diretamente no banco

---

## Arquitetura Obrigatória

```plaintext
todo-list-project/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── README.md
│
├── backend/
│   ├── index.php
│   ├── config/
│   │   └── database.php
│   └── README.md
│
├── specification/
│   ├── ui-specification.md
│   └── development.md
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
│
└── README.md
```

---

## Requisitos Funcionais

A aplicação deve permitir:

* Adicionar tarefas
* Listar tarefas
* Marcar como concluída
* Remover tarefas
* Filtrar tarefas:

  * Todas
  * Ativas
  * Completas
* Exibir contadores:

  * Total
  * Ativas
  * Completas

---

## Requisitos Não Funcionais

* Código organizado e legível
* Separação clara entre front-end e back-end
* Responsividade
* Estrutura escalável
* Boas práticas de Git

---

## Regras de Negócio

* Não permitir tarefas vazias
* Cada tarefa deve possuir:

  * id único
  * descrição
  * status (ativa ou completa)
* Interface deve refletir alterações em tempo real
* Contadores devem ser sempre consistentes
* Filtros devem funcionar corretamente

---

## Versionamento (OBRIGATÓRIO)

Utilizar commits semânticos:

```plaintext
feat: nova funcionalidade  
fix: correção de erro  
style: alterações visuais  
refactor: melhoria de código  
```

---

## Diretriz de Desenvolvimento (IMPORTANTE)

### Etapa 1 — Base (em aula)

Você deverá desenvolver a **estrutura base junto com o professor**.

Todos devem ter o mesmo ponto de partida funcional.

---

### Etapa 2 — Personalização (Individual)

Após finalizar a base, você deverá:

* Melhorar o design
* Criar uma identidade visual própria
* Diferenciar sua aplicação das demais
* Adicionar melhorias de UX (animações, feedback visual, etc.)

📌 Utilize como referência obrigatória:

* `ui-specification.md`
* `development.md`

---

## 🌿 Fluxo com Branch (OBRIGATÓRIO)

A personalização **NÃO deve ser feita na branch principal**.

### 1. Criar uma branch:

```plaintext
feature/ui-improvement-<seu-nome>
```

### 2. Desenvolver suas melhorias nessa branch

### 3. Enviar para o repositório

### 4. Abrir uma Pull Request

---

## 🚨 Requisitos da Pull Request (OBRIGATÓRIO)

Sua Pull Request deverá conter obrigatoriamente:

### 📌 Links

* 🔗 Link do repositório com a **versão base (sem melhorias)**
* 🔗 Link do repositório com a **versão final (com melhorias)**
* 🎨 Link do **Figma (ou ferramenta de design)** com o layout planejado

---

### 📌 Descrição

* O que foi alterado
* Quais melhorias foram implementadas
* Quais decisões de design foram tomadas

---

### 📌 Evidências

* Prints da aplicação
* (Opcional) GIF ou vídeo curto demonstrando interações

---

### 📌 Tipo de alteração

* UI/UX
* Refactor
* Feature
* Bugfix

---

## Documentação

Você deve criar:

### `README.md` (raiz)

* Descrição do projeto
* Objetivo
* Estrutura

### `frontend/README.md`

* Explicação da interface
* Como executar

### `backend/README.md`

* Planejamento do backend

---

## 🧾 Templates obrigatórios

### 📌 `bug_report.md`

* Descrição
* Passos
* Resultado esperado

### 📌 `pull_request_template.md`

* Nome completo
* Turma
* Data
* RA
* Descrição da entrega
* Links obrigatórios
* Checklist

---

## 📦 Entregáveis

* Repositório estruturado corretamente
* Front-end funcional mínimo
* Personalização visual aplicada
* Documentação inicial
* Uso de commits semânticos
* Criação de branch individual
* Pull Request completa (com todos os links obrigatórios)

---

## ⏰ Prazo

📌 **Entrega até o dia 20/03 às 22h30**

⚠️ A presença está condicionada ao envio da Pull Request dentro do prazo.

---

Se quiser, posso ainda:

* criar os arquivos `ui-specification.md` e `development.md` já prontos pra você só colar no repo
* ou montar um template de avaliação baseado nesses docs 👀
