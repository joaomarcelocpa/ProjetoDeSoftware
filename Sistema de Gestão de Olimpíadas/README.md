# 🏅 Sistema de Gestão de Olimpíadas

> Documentação técnica e diagramas arquiteturais do sistema de gerenciamento de eventos olímpicos.

## 📋 Sobre o Projeto

Este repositório contém a documentação completa e os principais diagramas UML do Sistema de Gestão de Olimpíadas, desenvolvido para gerenciar eventos, atletas, competições e resultados de olimpíadas.

---

## 🎯 Diagramas UML

### 1. Diagrama de Casos de Uso

Representa as principais funcionalidades do sistema e a interação dos usuários com essas funcionalidades.

![Diagrama de Casos de Uso](./Diagrama%20de%20Casos%20de%20Uso.jpeg)

---

### 2. Diagrama de Classes com Pacotes

Estrutura detalhada das classes do sistema, seus atributos, métodos e relacionamentos, organizados em pacotes lógicos.

![Diagrama de Classes com Pacotes](./Diagrama%20de%20Classes%20com%20Pacotes.jpeg)

---

### 3. Diagrama de Componentes

Visualização da organização dos componentes do sistema e suas dependências.

![Diagrama de Componentes](./Diagrama%20de%20Componentes.jpeg)

---

### 4. Diagrama de Implantação

Representa a infraestrutura física e a distribuição dos componentes nos nós de hardware.

![Diagrama de Implantação](./Diagrama%20de%20Implantação.jpeg)

---

## 👥 Histórias de Usuário

### US01: Cadastro de Atleta
**Como** atleta 
**Eu quero** me inscrever com minhas informações pessoais e modalidades  
**Para que** eu possa participar das competições

**Critérios de Aceitação:**
- O sistema deve permitir inserir nome, país, data de nascimento e modalidade do atleta
- Deve validar se o atleta já está cadastrado no sistema
- Deve ser possível associar múltiplas modalidades a um atleta
- O cadastro deve gerar um número único de identificação

---

### US02: Agendamento de Competições
**Como** administrador de eventos  
**Eu quero** agendar competições com data, horário e local  
**Para que** os atletas e espectadores saibam quando e onde ocorrerão as provas

**Critérios de Aceitação:**
- O sistema deve permitir selecionar modalidade, data, horário e local
- Deve validar conflitos de horário no mesmo local
- Deve ser possível visualizar o calendário completo de competições
- O sistema deve notificar atletas inscritos sobre o agendamento

---

### US03: Registro de Resultados
**Como** juiz  
**Eu quero** registrar os resultados das competições em tempo real  
**Para que** as classificações sejam atualizadas automaticamente

**Critérios de Aceitação:**
- O sistema deve permitir inserir tempos, pontos ou posições dos atletas
- Deve calcular automaticamente as classificações conforme as regras da modalidade
- Deve validar os dados inseridos (formato correto, valores válidos)
- Os resultados devem ser visíveis imediatamente após o registro

---

### US04: Consulta de Quadro de Medalhas
**Como** espectador ou mídia  
**Eu quero** visualizar o quadro de medalhas atualizado por país  
**Para que** eu possa acompanhar o desempenho das nações nas olimpíadas

**Critérios de Aceitação:**
- O sistema deve exibir medalhas de ouro, prata e bronze por país
- Deve permitir ordenação por total de medalhas ou por tipo
- O quadro deve ser atualizado automaticamente após cada competição
- Deve ser possível filtrar por modalidade específica

---

### US05: Gerenciamento de Locais de Competição
**Como** administrador do sistema  
**Eu quero** cadastrar e gerenciar os locais de competição  
**Para que** eu possa alocar adequadamente as provas e controlar a capacidade

**Critérios de Aceitação:**
- O sistema deve permitir cadastrar nome, endereço, capacidade e modalidades suportadas
- Deve ser possível visualizar a ocupação de cada local por data
- Deve alertar quando a capacidade do local for excedida
- Deve permitir editar e desativar locais quando necessário

---

## 🚀 Tecnologias

- UML (Unified Modeling Language)
- PlantUML
- Figma
- Draw.io

## 📝 Sobre

Este projeto é parte de um trabalho acadêmico da disciplina de Projeto de Software.

---

**Desenvolvido por Bernardo de Resende Marcelino e João Marcelo Carvalho Pereira Araújo**
