# Documento de Requisitos de Sistema

**Projeto:** [Nome do projeto/sistema]
**Versão do documento:** 1.0
**Data:** [DD/MM/AAAA]
**Autor(es):** [Nome(s)]
**Aprovado por:** [Nome / cargo]

---

## 1. Visão Geral

### 1.1 Propósito

[Descreve, em 2-3 frases, o objetivo deste documento e do sistema web a ser desenvolvido.]

### 1.2 Âmbito do Sistema

[Descreve o que o sistema vai fazer, os seus principais módulos/funcionalidades e o que fica fora do âmbito.]

### 1.3 Público-Alvo do Documento

[Ex.: equipa de desenvolvimento, product owner, stakeholders, QA.]

### 1.4 Definições, Acrónimos e Abreviaturas

| Termo | Definição |
|---|---|
| [Termo] | [Definição] |

---

## 2. Contexto do Sistema

### 2.1 Perspetiva do Produto

[O sistema é novo, uma evolução de outro, ou integra-se com sistemas existentes?]

### 2.2 Utilizadores e Perfis (Personas)

| Perfil/Papel | Descrição | Principais objetivos no sistema |
|---|---|---|
| [Ex.: Administrador] | [Descrição] | [Objetivos] |
| [Ex.: Cliente final] | [Descrição] | [Objetivos] |

### 2.3 Ambiente Tecnológico

- **Frontend:** [tecnologias/framework, ex. React, navegadores suportados]
- **Backend:** [tecnologias/framework]
- **Base de dados:** [tipo/tecnologia]
- **Hospedagem/Infraestrutura:** [cloud, on-premise, etc.]
- **Integrações externas:** [APIs, serviços de terceiros]

---

## 3. Requisitos Funcionais

> Organizados por épico/funcionalidade, no estilo de user stories (adequado a metodologia ágil).

### Épico: [Nome do Épico, ex. Autenticação]

**RF-001 — [Título curto da funcionalidade]**
- **User Story:** Como [perfil de utilizador], quero [ação/funcionalidade], para [benefício/objetivo].
- **Critérios de Aceitação:**
  - [ ] [Critério 1]
  - [ ] [Critério 2]
  - [ ] [Critério 3]
- **Prioridade:** [Alta / Média / Baixa]
- **Estimativa:** [Story points / horas]
- **Dependências:** [Outros requisitos, se aplicável]

**RF-002 — [Título curto da funcionalidade]**
- **User Story:** Como [perfil], quero [ação], para [benefício].
- **Critérios de Aceitação:**
  - [ ] [Critério 1]
  - [ ] [Critério 2]
- **Prioridade:** [Alta / Média / Baixa]
- **Estimativa:** [Story points / horas]

*(Repetir estrutura para cada épico/funcionalidade)*

---

## 4. Requisitos Não Funcionais

| ID | Categoria | Requisito | Critério de Aceitação/Métrica |
|---|---|---|---|
| RNF-001 | Desempenho | [Ex.: Tempo de resposta das páginas] | [Ex.: < 2s em 95% dos pedidos] |
| RNF-002 | Segurança | [Ex.: Autenticação e encriptação] | [Ex.: HTTPS obrigatório, dados sensíveis cifrados] |
| RNF-003 | Usabilidade | [Ex.: Responsividade / acessibilidade] | [Ex.: Compatível com WCAG 2.1 AA] |
| RNF-004 | Disponibilidade | [Ex.: Uptime do sistema] | [Ex.: 99,5% mensal] |
| RNF-005 | Escalabilidade | [Ex.: Capacidade de utilizadores simultâneos] | [Ex.: Suportar X utilizadores concorrentes] |
| RNF-006 | Compatibilidade | [Ex.: Navegadores/dispositivos suportados] | [Ex.: Chrome, Firefox, Safari - últimas 2 versões] |
| RNF-007 | Manutenibilidade | [Ex.: Cobertura de testes] | [Ex.: > 80% de cobertura] |

---

## 5. Regras de Negócio

| ID | Regra | Descrição |
|---|---|---|
| RN-001 | [Nome da regra] | [Descrição detalhada da regra de negócio] |

---

## 6. Restrições e Premissas

### 6.1 Restrições

- [Ex.: Orçamento, prazos, tecnologia obrigatória, conformidade legal/regulatória (RGPD, etc.)]

### 6.2 Premissas

- [Ex.: Disponibilidade de dados, dependência de equipas externas]

---

## 7. Backlog Priorizado (Resumo)

| ID | Funcionalidade | Épico | Prioridade | Status |
|---|---|---|---|---|
| RF-001 | [Nome] | [Épico] | Alta | Por fazer |
| RF-002 | [Nome] | [Épico] | Média | Por fazer |

---

## 8. Critérios de Aceitação do Sistema (Definition of Done)

- [ ] Todos os requisitos funcionais implementados e testados
- [ ] Requisitos não funcionais validados
- [ ] Testes de aceitação aprovados pelo stakeholder
- [ ] Documentação técnica atualizada
- [ ] Sem bugs críticos ou bloqueantes em aberto

---

## 9. Histórico de Revisões

| Versão | Data | Autor | Descrição da alteração |
|---|---|---|---|
| 1.0 | [DD/MM/AAAA] | [Nome] | Criação do documento |

---

## 10. Anexos
[Wireframes, diagramas, mockups, links para protótipos, etc.]