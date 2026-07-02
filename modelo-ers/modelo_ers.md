# Especificação de Requisitos de Sistema (ERS) - [Nome do Projeto]

> SRS - Software Requirements Specification. É a fonte única de verdade que descreve:
>
> - requisitos das funcionalidades
> - comportamentos
> - critérios de qualidade

## 1. Introdução

### 1.1 Objetivo do Documento

explicar a finalidade do SRS e o público-alvo.

### 1.2 Escopo do Sistema

descrever resumidamente o que o software faz e o que está fora do escopo.

### 1.3 Glossário (Linguagem Ubíqua)

listar termos técnicos e abreviações usadas ao longo do documento

## 2. Descrição Geral

### 2.1 Perspectiva do Produto

### 2.2 Funções do Produto (Resumo)

### 2.3 Características dos Usuários (Atores)

### 2.4 Restrições Gerais e Premissas

## 3. Requisitos Funcionais (RF)

Cada requisito deve ser específico, mensurável e testável.

Ao redigir requisitos funcionais, evite termos vagos como “o sistema deve ser rápido” ou “a interface deve ser intuitiva”. Prefira métricas quantificáveis, como tempos de resposta ou taxas de erro aceitáveis.

Pode dividir em épico (exemplo Épico: [Nome do Épico, ex. Autenticação])

exemplo simples:

**RF-001:** o sistema deve permitir que o usuário crie uma conta utilizando endereço de e-mail e senha, com confirmação por e-mail em até dois minutos.

exemplos mais completo:

- **RF001: [Nome do Requisito]**
  - **Descrição:** [O que a funcionalidade faz]; ou
  - **User Story:** Como [perfil de utilizador], quero [ação/funcionalidade], para [benefício/objetivo].
  - **Atores:** [Quem utiliza]
  - **Critérios de Aceitação:**
    - [ ] [Critério 1]
    - [ ] [Critério 2]
    - [ ] [Critério 3]
  - **Prioridade:** [Alta/Média/Baixa]
  - **Dependências:** [Outros requisitos, se aplicável]
- **RF002: ...**

## 4. Requisitos Não-Funcionais (RNF)

definem os critérios de qualidade que o sistema deve atender

- **RNF001: [Arquitetura/Stack]** - Ex: O sistema deve ser desenvolvido utilizando...
- **RNF002: [Segurança]** - Ex: Autenticação via JWT, controle de acessos (RBAC)...
- **RNF003: [Desempenho/Disponibilidade]**

## 5. Requisitos externos da interface

Os requisitos de interface definem como o sistema se comunica com elementos externos.

**Interface do usuário**: descreve o layout, os elementos visuais e os padrões de navegação que o sistema deve seguir.

**Interface de hardware**: especifica as interações com dispositivos físicos, como impressoras, leitores de código de barras ou sensores.

**Interface de software**: documenta as integrações com outros sistemas, APIs ou bases de dados.

**Interface de comunicação**: detalha os protocolos de rede, formatos de mensagens e requisitos de conectividade.

## 6. Regras de Negócio (RN)

- **RN001:** [Restrição ou cálculo específico]

## 7. Referências e Anexos

indicar outros documentos relacionados, como especificações de arquitetura, planos de projeto, especificação de funcionalidades

- ESPEC 01 Funcionalidade 01

## Considerações Gerais

- O documento deve descrever **o que o sistema faz**, e não como será implementado.
- Banco de dados, APIs, arquitetura, infraestrutura e deploy devem ser documentados em documentos específicos.
- Utilize linguagem ubíqua em todo o documento.
- Cada Feature deve ser autocontida, permitindo implementação independente por desenvolvedores ou agentes de IA.
- Sempre que possível, relacione Casos de Uso, User Stories, Regras de Negócio e Requisitos Funcionais.
