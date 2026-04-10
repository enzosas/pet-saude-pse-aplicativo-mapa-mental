---
markmap:
  maxWidth: 200
  spacingVertical: 20
---

COLAR ESSE ARQUIVO (INCLUINDO ESSE CABEÇALHO ACIMA) NO SITE https://markmap.js.org/repl

# Reunião educarweb
## Nota: seria interessante que eles conseguissem desenvolver em no máximo 2 semanas
## Objetivos da solução deles
### Dar o mínimo de trabalho possível para os professores
## Possiveis soluções disponibilizadas por eles

### Botão que gere pdf da turma com nome e nascimento
#### Prós 
##### Acho que nenhum, seria das alternativas a pior, mas ainda assim satisfaria nosso objetivo
#### Contras
##### deverá ser por nós elaborado um jeito de fazer os professores pelo menos uma vez enviarem para nosso sistema as turmas
### [IDEAL] Rota que nós tenhamos acesso que retorne json com alunos e nascimento
#### Prós 
##### não envolverá qualquer tipo de pré registro das turmas pelos professores 
#### Contras 
##### Não sei como seria a parte de segurança/autenticação da rota
##### Não sei que tipos de ids usariamos para acessar alguma turma especifica
##### Eles vão demorar um monte pra fazer

## Cenário em que eles não fazem nada
### Extrair dados daquele pdf que contem dados sensiveis
#### Envolve os professores enviarem o pdf para algum responsável por nosso sistema para gerar o banco de tal turma para nosso sistema

# Desenvolvimento do App
## Fluxo
- Login(?)
- [botao] Preencher relatorio PSE
- Preencher Escola
- Preencher Data
- Selecionar turma para importar alunos e nascimentos
- Dos alunos importados, marcar os ausentes
  - deixar como default o check de presença para agilizar o preenchimento 
- preencher para cada aluno o peso e altura
  - parte mais tediosa, algum jeito de melhorar?
- [botao] finalizar
  - possibilidades
    - enviar dados para sistema automatizado que realize cadastro no mv
    - gerar pdf
## Questões
- Haverá login dos professores?
  - Se sim, existe algum jeito de conectar esse login com o educarweb?
    - importante para facilitar a escolha da turma na hora de preencher a "folha" do PSE
    - existe algum jeito de evitar de o professor precisar criar o seu cadastro?



