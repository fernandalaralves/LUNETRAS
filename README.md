# LUNETRAS

## 📚 Descrição do Sistema

O **LUNETRAS** é um **Sistema Web educacional** voltado para o apoio ao processo de alfabetização nos anos iniciais do Ensino Fundamental. Seu principal objetivo é **avaliar, registrar, classificar e acompanhar** o nível de maturidade necessário para a aprendizagem da **leitura e da escrita** dos alunos, com base na **Psicogênese da Língua Escrita**, conforme os estudos de **Emília Ferreiro e Ana Teberosky**.

O sistema foi concebido para substituir registros manuais, promovendo **automatização**, **economia de tempo**, **sustentabilidade** e **maior precisão dos dados pedagógicos**, auxiliando professores e coordenadores na tomada de decisões educacionais.

---

## 👩‍💻 Autores

* Alissa Garcia
* Fernanda Lara
* José Ailton
* Tainá Rodrigues
* Wesley Santos

---

## 🎯 Objetivo Geral

Criar um sistema que auxilie professores do **Ensino Fundamental I (1º ao 3º ano)** na avaliação, registro e acompanhamento dos protocolos de leitura e escrita, de acordo com a psicogênese da língua escrita, permitindo uma análise clara da evolução dos alunos ao longo do tempo.

---

## 🧠 Visão Geral do Produto

O produto consiste em um **software educacional de registro de avaliações de leitura e escrita**, capaz de:

* Registrar avaliações diagnósticas e periódicas
* Classificar alunos por nível psicogenético
* Quantificar dados por turma, série e período
* Gerar relatórios gráficos e tabelas
* Acompanhar a evolução individual e coletiva

### Problemas que o sistema resolve

* Alto consumo de tempo com registros manuais
* Falta de padronização nas avaliações
* Dificuldade no acompanhamento longitudinal dos alunos
* Risco de perda ou inconsistência de dados

---

## 📌 Especificações Iniciais do Software

### Objetivo do Produto

Auxiliar professores do Ensino Fundamental I na **avaliação, registro e acompanhamento do desenvolvimento da leitura e escrita**, oferecendo uma ferramenta digital prática, intuitiva e pedagógica.

### Problemática

Durante os períodos avaliativos (trimestrais ou bimestrais), os alunos são classificados nos seguintes níveis psicogenéticos:

* Icônica
* Garatuja
* Pré-silábico
* Silábico
* Silábico-Alfabético
* Alfabético

Esses registros, quando feitos manualmente, tornam-se morosos e difíceis de analisar ao longo do tempo.

### Motivação e Justificativa

O LUNETRAS surge da necessidade de **automatizar** e **organizar** esse processo avaliativo, reduzindo erros e facilitando a análise pedagógica. Observa-se também uma lacuna no mercado por ferramentas que integrem diretamente a psicogênese da língua escrita ao cotidiano escolar.

---

## 🏫 Contexto de Uso

* Escolas públicas e privadas
* Turmas do 1º ao 3º ano do Ensino Fundamental
* Ambientes com acesso à internet
* Uso em computadores, tablets ou celulares

O sistema está alinhado às demandas atuais por **digitalização**, **proteção de dados** e **organização pedagógica**.

---

## 🚀 Aplicabilidade

O LUNETRAS pode ser utilizado em:

* Avaliações diagnósticas
* Avaliações periódicas
* Acompanhamento da alfabetização
* Análise de turmas e séries
* Apoio à coordenação pedagógica

---

## ✅ Benefícios Esperados

* Redução do tempo gasto com avaliações
* Maior precisão nos registros
* Padronização dos dados pedagógicos
* Relatórios automáticos e visuais
* Suporte à tomada de decisão docente
* Organização e histórico das avaliações

---

## 👥 Público-Alvo

* Professores do 1º ao 3º ano
* Coordenadores pedagógicos

**Perfil:**

* Formação em Pedagogia
* Faixa etária entre 22 e 60 anos
* Conhecimento básico em tecnologia
* Necessidade de ferramentas simples e intuitivas

---

## 🧩 Funcionalidades do Sistema

### 🔐 Autenticação

* Login por e-mail
* Senha criptografada
* Perfis de acesso (Administrador e Professor)

### 👩‍💼 Visão do Administrador

* Cadastro de turmas
* Cadastro de professores (com geração automática de senha)
* Cadastro de alunos (nome e data de nascimento)
* Definição de horários e vagas

### 👨‍🏫 Visão do Professor

* Visualizar turmas
* Visualizar alunos
* Classificar alunos por nível psicogenético
* Registrar observações pedagógicas

📌 **Regra de Negócio:**

* Cada aluno pode ser classificado em **apenas um nível por bimestre**
* Transições de níveis devem constar nas observações

### 📊 Relatórios

* Quantidade de alunos por nível
* Quantidade de níveis por turma
* Gráficos e tabelas comparativas
* Apoio à análise da adequação do nível à série (faixa etária x qualificação)

---

## 🏗 Arquitetura do Sistema

### Arquitetura em Camadas

* **Apresentação (Frontend)**: Interface do usuário
* **Aplicação/Negócio (Backend)**: Regras de negócio e validações
* **Persistência (Banco de Dados)**: Armazenamento dos dados

---

## 🧪 Tecnologias Utilizadas

### Backend

* API REST
* Linguagem sugerida: Java / Node.js / Python (definição conforme equipe)
* Autenticação e criptografia de senhas

### Frontend

* Interface Web Responsiva
* HTML, CSS e JavaScript
* Framework sugerido: React ou Vue.js

### Banco de Dados

* Relacional (MySQL ou PostgreSQL)
* Estrutura normalizada para alunos, turmas, avaliações e usuários

---

## 🗂 Modelagem do Sistema

### Principais Entidades

* Usuário
* Professor
* Administrador
* Aluno
* Turma
* Avaliação
* Nível Psicogenético
* Observações
* Relatórios

---

## 📌 Considerações Finais

O **LUNETRAS** é uma solução educacional que une tecnologia e pedagogia, contribuindo para uma alfabetização mais organizada, eficiente e fundamentada em teorias reconhecidas. O sistema visa fortalecer o trabalho docente e apoiar a evolução da aprendizagem dos alunos de forma clara e mensurável.
