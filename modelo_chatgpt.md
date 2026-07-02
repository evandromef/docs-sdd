# Modelo de Documento de Requisitos do Sistema (DRS)

> Documento enxuto para projetos ágeis (Scrum + SDD), utilizando
> linguagem ubíqua e voltado ao desenvolvimento por equipes e agentes de
> IA.

------------------------------------------------------------------------

# 1. Informações do Documento

  Campo                Valor
  -------------------- ---------------------------------------
  Sistema              
  Versão               
  Status               Em elaboração / Em revisão / Aprovado
  Autor(es)            
  Data                 
  Última atualização   

## Histórico de Alterações

  Versão   Data   Autor   Descrição
  -------- ------ ------- -----------
  0.1                     

------------------------------------------------------------------------

# 2. Objetivo

Descreva o objetivo do sistema de forma clara e objetiva.

------------------------------------------------------------------------

# 3. Escopo

## O sistema deve

-   ...

## O sistema não deve

-   ...

------------------------------------------------------------------------

# 4. Glossário (Linguagem Ubíqua)

  Termo   Definição
  ------- -----------
          

------------------------------------------------------------------------

# 5. Personas (Opcional)

## Persona

**Nome**

**Descrição**

**Objetivos**

**Necessidades**

------------------------------------------------------------------------

# 6. Funcionalidades

> Organize o documento por Feature.

------------------------------------------------------------------------

# Feature: `<Nome da Funcionalidade>`{=html}

## Objetivo

Descreva o objetivo da funcionalidade.

------------------------------------------------------------------------

## Casos de Uso

### UC-001 - Nome

**Objetivo**

**Atores**

**Pré-condições**

### Fluxo Principal

1.  
2.  
3.  

### Fluxos Alternativos

-   

### Fluxos de Exceção

-   

### Pós-condições

-   

### Regras relacionadas

-   RN-001

------------------------------------------------------------------------

## User Stories

### US-001

**Como** ...

**Quero** ...

**Para** ...

------------------------------------------------------------------------

## Requisitos Funcionais

### RF-001 - Nome

**Descrição**

**Motivação**

**Entradas**

**Saídas**

**Critérios de Aceitação**

-   \[ \]

**Prioridade**

-   Alta
-   Média
-   Baixa

**Dependências**

**Casos de Uso Relacionados**

**User Stories Relacionadas**

------------------------------------------------------------------------

## Regras de Negócio

### RN-001

**Descrição**

**Motivação**

**Exemplos**

**Exceções**

**Requisitos Relacionados**

------------------------------------------------------------------------

## Requisitos Não Funcionais (quando aplicável)

### RNF-001

**Categoria**

-   Performance
-   Segurança
-   Disponibilidade
-   Escalabilidade
-   Observabilidade
-   Outro

**Descrição**

**Critério**

------------------------------------------------------------------------

## Fluxos

### Fluxo Principal

Descreva o fluxo principal.

### Fluxos Alternativos

Descreva os fluxos alternativos.

### Fluxos de Exceção

Descreva os fluxos de exceção.

------------------------------------------------------------------------

## Diagramas

### Diagrama de Caso de Uso

> Inserir diagrama UML

### Diagrama de Sequência

> Inserir diagrama UML

------------------------------------------------------------------------

## Contexto para IA

### Objetivo

### Dependências

### Regras que devem ser respeitadas

### Critérios de Aceitação

### Observações

------------------------------------------------------------------------

## Checklist de Implementação

-   [ ] Requisitos revisados
-   [ ] Regras de negócio documentadas
-   [ ] Fluxos definidos
-   [ ] Critérios de aceitação definidos
-   [ ] Diagramas atualizados
-   [ ] Contexto para IA revisado
-   [ ] Pronto para desenvolvimento

------------------------------------------------------------------------

# Considerações Gerais

-   O documento deve descrever **o que o sistema faz**, e não como será
    implementado.
-   Banco de dados, APIs, arquitetura, infraestrutura e deploy devem ser
    documentados em documentos específicos.
-   Utilize linguagem ubíqua em todo o documento.
-   Cada Feature deve ser autocontida, permitindo implementação
    independente por desenvolvedores ou agentes de IA.
-   Sempre que possível, relacione Casos de Uso, User Stories, Regras de
    Negócio e Requisitos Funcionais.
