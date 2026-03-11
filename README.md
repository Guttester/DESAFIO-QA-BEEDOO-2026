# DESAFIO-QA-BEEDOO-2026

## Analista de Qualidade de Software Júnior – Beedoo

**QA Responsável:** Augusto Henrique do Espirito Santo  
**Data de entrega:** 11/03/2026 - 03:00

---

# 0. Análise preliminar da aplicação

A aplicação apresenta uma estrutura simples que simula um módulo básico de gerenciamento de cursos, seguindo parcialmente o conceito de um CRUD (Create, Read, Update, Delete).

Atualmente a aplicação contempla principalmente os fluxos de:

- Cadastro de cursos (Create)
- Listagem de cursos (Read)
- Exclusão de cursos (Delete)

Não foi identificada a implementação da funcionalidade de **edição (Update)**, o que indica que a aplicação ainda se encontra em uma versão inicial ou de demonstração.

Outro ponto observado é a ausência de validações mais rígidas no formulário, como campos obrigatórios ou restrições de consistência de dados. Essas validações seriam importantes em versões futuras para garantir maior integridade das informações cadastradas.

---

# 1. Fluxos principais identificados

Durante a exploração da aplicação foram identificados dois fluxos principais:

## Cadastro de cursos
1. Acessar tela de cadastro
2. Preencher informações do curso
3. Registrar curso no sistema

## Listagem de cursos
1. Visualizar cursos cadastrados
2. Exibir informações dos cursos em cards
3. Possibilidade de exclusão de cursos

---

# 2. Pontos críticos para testes

Os principais pontos considerados críticos foram:

- Validação de campos do formulário
- Consistência das datas (data início e data fim)
- Persistência das informações cadastradas
- Organização visual dos cards na listagem
- Funcionamento da exclusão de cursos
- Comunicação entre frontend e backend

---

# 3. Estratégia de testes

A estratégia adotada considerou:

- Fluxos principais da aplicação
- Cenários positivos
- Cenários negativos
- Validação de campos
- Comportamentos inesperados

Os cenários foram documentados utilizando estrutura **Gherkin (Given / When / Then)**.

---

# 4. Cenários e casos de teste

### Overview da execução dos testes

Durante a execução dos testes foram avaliados os fluxos principais do módulo de cursos, incluindo cadastro e listagem.

Ao todo foram executados **15 cenários de teste**, distribuídos entre funcionalidades críticas da aplicação.

**Resultados da execução:**

- **11 cenários passaram (PASSED)** demonstrando funcionamento esperado em parte das funcionalidades.
- **4 cenários falharam (FAILED)** indicando inconsistências relacionadas a validações, layout e comportamento funcional da aplicação.
- Não foram identificados cenários bloqueados ou pendentes durante a execução.

Os cenários foram organizados em dois grupos principais:

- **Cadastro de cursos** – validação de campos, consistência de dados e registro das informações.
- **Listagem de cursos** – validação de navegação, organização dos cards e comportamento da interface.

A imagem abaixo apresenta um resumo consolidado da execução dos cenários de teste.

![View Board](https://github.com/Guttester/DESAFIO-QA-BEEDOO-2026/blob/main/View-board.png?raw=true)

Os cenários e casos de teste foram documentados em uma planilha.

![Cenários de Teste](https://raw.githubusercontent.com/Guttester/DESAFIO-QA-BEEDOO-2026/main/Cen%C3%A1rios.png)

**Planilha de testes:**  
https://docs.google.com/spreadsheets/d/1HULq2tFXZiGUQ7YqYXq_vwt0NQQ2x62PaSFZ4MRtR8E/edit?usp=sharing

---

# 5. Execução dos testes

Os testes foram executados manualmente na aplicação disponibilizada para o desafio:

https://creative-sherbet-a51eac.netlify.app/

Durante a execução foram identificados:

- comportamentos esperados
- inconsistências de layout
- falhas de validação
- falhas funcionais

---

# 6. Bugs encontrados

Os bugs identificados durante a execução estão documentados em:

**Relatório de Bugs:**  
https://drive.google.com/drive/folders/1A6_XZLN3CSsbg9Pq__d-0Jl0aIWEf1Ec?usp=drive_link

Cada bug contém:

- título do bug
- passos para reproduzir
- resultado atual
- resultado esperado
- severidade
- evidência

---

# 7. Evidências da execução

As evidências da execução dos testes podem ser acessadas no link abaixo:

https://drive.google.com/drive/folders/1BcOyzFoNUm_3ET5Sfqsq2Co9Tm6aXQCG?usp=drive_link

---

# 8. Uso de Inteligência Artificial

Ferramentas de IA foram utilizadas como apoio para organização da documentação e revisão estrutural dos cenários de teste.

As decisões de análise e definição dos cenários foram realizadas de forma crítica durante a exploração da aplicação.

---

# 9. Considerações finais

O desafio permitiu analisar aspectos importantes de qualidade de software, incluindo:

- modelagem de cenários de teste
- identificação de defeitos
- análise de comportamento do sistema

A documentação buscou manter clareza, rastreabilidade entre cenários e bugs e organização da entrega.
