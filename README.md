# DESAFIO-QA-BEEDOO-2026

## Analista de Qualidade de Software Júnior – Beedoo

**QA Responsável:** Augusto Henrique do Espirito Santo<br>
**Data de entrega:** 11/03/2026 - 03:00

---

# 1. Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e a listagem de cursos.  
O sistema disponibiliza um formulário para registro de cursos e uma tela para visualização dos cursos cadastrados.

---

# 2. Fluxos principais identificados

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

# 3. Pontos críticos para testes

Os principais pontos considerados críticos foram:

- Validação de campos do formulário
- Consistência das datas (data início e data fim)
- Persistência das informações cadastradas
- Organização visual dos cards na listagem
- Funcionamento da exclusão de cursos
- Comunicação entre frontend e backend

---

# 4. Estratégia de testes

A estratégia adotada considerou:

- Fluxos principais da aplicação
- Cenários positivos
- Cenários negativos
- Validação de campos
- Comportamentos inesperados

Os cenários foram documentados utilizando estrutura Gherkin (Given / When / Then).

---

# 5. Cenários e casos de teste

Os cenários e casos de teste foram documentados em uma planilha.

**Planilha de testes:**  
https://docs.google.com/spreadsheets/d/1HULq2tFXZiGUQ7YqYXq_vwt0NQQ2x62PaSFZ4MRtR8E/edit?usp=sharing

---

# 6. Execução dos testes

Os testes foram executados manualmente na aplicação disponibilizada:

https://creative-sherbet-a51eac.netlify.app/

Durante a execução foram identificados:

- comportamentos esperados
- inconsistências de layout
- falhas de validação
- falhas funcionais

---

# 7. Bugs encontrados

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

# 8. Evidências da execução

As evidências da execução dos testes podem ser acessadas no link abaixo:

https://drive.google.com/drive/folders/1BcOyzFoNUm_3ET5Sfqsq2Co9Tm6aXQCG?usp=drive_link

---

# 9. Uso de Inteligência Artificial

Ferramentas de IA foram utilizadas como apoio para organização da documentação e revisão estrutural dos cenários de teste.

As decisões de análise e definição dos cenários foram realizadas de forma crítica durante a exploração da aplicação.

---

# 10. Considerações finais

O desafio permitiu analisar aspectos importantes de qualidade de software, incluindo:

- modelagem de cenários de teste
- identificação de defeitos
- análise de comportamento do sistema

A documentação buscou manter clareza, rastreabilidade entre cenários e bugs e organização da entrega.
