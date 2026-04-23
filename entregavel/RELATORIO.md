# 📦 Relatório Final

> **Atividade:** Bug Report Profissional + Code Review Guiado
> **Curso:** Qualidade de Software
> **Professor:** Prof. Claudio Nunes

---

## 👥 Identificação da dupla

| Nome completo | RA | GitHub |
|---|---|---|
| [Daniel Gomiero] | [229802] | [@danigomiero7] |
| [Julia Correia] | [228380] | [@julisboa10] |

**Ambiente de testes:** GitHub Pages do fork

---

## 📋 Sumário

- [Parte A — Bug Reports](#parte-a--bug-reports)
- [Parte B — Code Review](#parte-b--code-review)
- [Reflexão final](#-reflexão-final)
- [Declarações](#-declarações)

---

## Parte A — Bug Reports

 Bug 1
Título:
Sistema permite criar tarefa sem preencher campos obrigatórios

Passos para reprodução:
1.	Acessar a aplicação
2.	Não preencher nenhum campo do formulário
3.	Clicar em "Adicionar tarefa"

Resultado esperado:
O sistema deve impedir a criação da tarefa e exibir mensagem de validação

Resultado atual:
A tarefa é criada mesmo com todos os campos vazios

Severidade: Crítica
Prioridade: P1

Categoria: Validação / Funcional

Evidência:
<img width="1920" height="809" alt="1" src="https://github.com/user-attachments/assets/a2ccc333-d15c-43a7-ac35-3cf9bf7d3026" />



 Bug 2
Título:
Campo de prioridade aceita valores fora do intervalo permitido

Passos para reprodução:
1.	Preencher o título normalmente
2.	Inserir no campo prioridade valores como "0", "-1" ou "99"
3.	Clicar em "Adicionar tarefa"

Resultado esperado:
O sistema deve aceitar apenas valores entre 1 e 5

Resultado atual:
O sistema aceita qualquer valor numérico

Severidade: Alta
Prioridade: P1

Categoria: Validação

Evidência:
<img width="1901" height="944" alt="2" src="https://github.com/user-attachments/assets/4d5d5c8f-079d-437e-afea-41b1efc0d8b3" />


 


Bug 3
Título:
Tarefas são perdidas ao recarregar a página

Passos para reprodução:
1.	Criar uma ou mais tarefas
2.	Atualizar a página (F5)

Resultado esperado:
As tarefas deveriam permanecer salvas após recarregar

Resultado atual:
Todas as tarefas desaparecem após o reload

Severidade: Crítica
Prioridade: P1

Categoria: Persistência

Evidência:
<img width="1920" height="906" alt="3" src="https://github.com/user-attachments/assets/0634e13a-bec5-4acb-b754-84102d038f55" /> 


---

## Parte B — Code Review

> **Substitua este bloco de citação pelo conteúdo copiado integralmente do seu arquivo `parte-b-code-review/formulario-code-review.md`.**
> Preservando os rótulos, linhas e sugestões de correção.
> Mínimo: 6 findings.

### Resumo

| # | Linha | Dimensão | Rótulo | Severidade |
|---|-------|----------|--------|------------|
| 1 |       |          |        |            |
| 2 |       |          |        |            |
| 3 |       |          |        |            |
| 4 |       |          |        |            |
| 5 |       |          |        |            |
| 6 |       |          |        |            |

### Findings detalhadas

> Cole integralmente aqui suas findings copiadas do formulário.

---

## 💭 Reflexão final

> Responda em 1-2 parágrafos. Esta reflexão **é obrigatória**.

**Qual dimensão do checklist foi mais difícil aplicar? Por quê?**

[Escrevam aqui.]

**O que vocês fariam diferente se revisassem o código novamente?**

[Escrevam aqui.]

---

## 📣 Declarações


### Uso de IA como parceiro de trabalho

- [ ] Não usamos IA nesta atividade.
- [ ] Usamos IA para esclarecer conceitos teóricos.
- [ ] Usamos IA para revisar a redação dos bug reports.
- [ ] Usamos IA para discutir se um achado era ou não um defeito.
- [ ] Uso específico: [descreva]

### Declaração de autoria

Declaramos que este relatório é de autoria da dupla, que exploramos
pessoalmente a aplicação da Parte A e lemos o código da Parte B. As
findings aqui registradas representam nosso próprio julgamento
técnico.
