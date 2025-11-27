# 📘 Desafio de Projeto – Plano de Aula Interativo e Personalizado com Ecossistema IA

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue)  ![CI](https://img.shields.io/github/actions/workflow/status/seuusuario/plano-aula-ia/main.yml?label=CI)  ![Licença](https://img.shields.io/badge/licença-MIT-green)  

---

## 📑 Índice
1. [Sobre o Projeto](#-sobre-o-projeto)  
2. [Objetivos de Aprendizagem](#-objetivos-de-aprendizagem)  
3. [Estrutura do Repositório](#-estrutura-do-repositório)  
4. [Plano de Aula](#-plano-de-aula)  
5. [Automação com GitHub Actions](#-automação-com-github-actions)  
6. [Recursos Úteis](#-recursos-úteis)  
7. [Entrega](#-entrega)  
8. [Conclusão](#-conclusão)  
9. [Quizzes](#-quizzes)  
10. [Como Contribuir](#-como-contribuir)  
11. [Licença](#-licença)  

---

## ✨ Sobre o Projeto
Este Desafio de Projeto tem como objetivo **criar um Plano de Aula Interativo e Personalizado com Ecossistema IA**.  
A proposta é aplicar conceitos de Inteligência Artificial em um contexto educacional, documentando todo o processo de forma clara e organizada para servir como portfólio e referência prática.

---

## 🎯 Objetivos de Aprendizagem
- Compreender os conceitos básicos de IA generativa  
- Explorar aplicações práticas em diferentes áreas  
- Desenvolver senso crítico sobre ética e segurança na IA  
- Utilizar ferramentas de IA para criar conteúdo interativo  
- Documentar e compartilhar conhecimento no GitHub  

---

## 🏗️ Estrutura do Repositório
```plaintext
plano-aula-ia/
├── README.md                  # Documentação principal
├── .markdownlint.json         # Configuração para validação Markdown
├── .github/workflows/main.yml # Workflow de automação
├── images/                    # Capturas de tela e diagramas (opcional)
└── docs/                      # Materiais complementares (opcional)
```

---

## 📚 Plano de Aula
**Tema:** Introdução à IA Generativa  
**Objetivo da Aula:** Apresentar conceitos básicos de IA generativa e demonstrar aplicações práticas.  

**Conteúdo Programático:**  
1. O que é IA generativa  
2. Principais modelos e aplicações (texto, imagem, código)  
3. Demonstração prática com Copilot / ChatGPT  
4. Discussão sobre ética e segurança  

**Metodologia:**  
- Exposição dialogada com slides  
- Atividade prática: criação de prompts e análise das respostas da IA  
- Interação em grupo: debate sobre riscos e benefícios  
- Documentação: registro da experiência no GitHub  

**Recursos Didáticos:**  
- Slides explicativos  
- Ferramentas de IA (Copilot, ChatGPT, DIO Labs)  
- GitHub para documentação  
- Quizzes interativos  

**Avaliação:**  
- Participação nas atividades práticas  
- Qualidade da documentação no GitHub  
- Reflexão crítica apresentada no debate  

---

## 🔄 Automação com GitHub Actions
Este projeto inclui um workflow para:
- ✅ Validar arquivos Markdown (README.md)
- ✅ Converter a apresentação (.pptx) para PDF automaticamente

### Como funciona:
1. Ao fazer push para a branch `main`, o GitHub Actions executa:
   - Validação do Markdown usando **markdownlint**
   - Conversão da apresentação para PDF usando **LibreOffice**

### Estrutura:
- `.github/workflows/main.yml` → Workflow principal  
- `.markdownlint.json` → Configuração de validação Markdown  

### Benefícios:
- Garantia de qualidade na documentação  
- Automação da geração de PDF para compartilhamento  

---

## 🔗 Recursos Úteis
- https://docs.github.com/en/get-started  
- https://docs.github.com  
- https://www.markdownguide.org/basic-syntax/  
- https://www.dio.me – Plataforma de aprendizado e desafios  

---

## ✅ Entrega
Este repositório contém:  
- Um arquivo **README.md** detalhado  
- Estrutura organizada para documentação  
- Workflow de automação com GitHub Actions  
- Espaço para imagens e materiais complementares  

---

## 🚀 Conclusão
Este projeto demonstra como aplicar **IA e boas práticas de documentação** em um plano de aula interativo.  
Além de atender ao desafio da DIO, serve como portfólio para destacar habilidades técnicas e de comunicação.

---

## ✅ Quizzes

### Quiz 1 – Ética e Responsabilidade na IA

1. Qual é um dos principais desafios éticos da IA generativa?  
   - [ ] Aumentar produtividade  
   - [ ] Melhorar criatividade  
   - [x] Evitar vieses e desinformação  
   - [ ] Reduzir custos

2. O que significa "transparência algorítmica"?  
   - [ ] Tornar os algoritmos secretos  
   - [x] Explicar como os modelos tomam decisões  
   - [ ] Esconder dados de treinamento  
   - [ ] Usar IA apenas em empresas privadas

3. Qual prática ajuda a reduzir vieses em IA?  
   - [ ] Usar menos dados  
   - [ ] Ignorar diversidade  
   - [x] Treinar com dados variados e representativos  
   - [ ] Focar apenas em dados de um país

---

### Quiz 2 – Aplicações Práticas da IA

1. Qual destas áreas já utiliza IA generativa de forma significativa?  
   - [ ] Agricultura  
   - [ ] Medicina  
   - [ ] Educação  
   - [x] Todas as anteriores

2. Em educação, qual é um uso positivo da IA generativa?  
   - [ ] Substituir professores  
   - [x] Criar materiais personalizados para alunos  
   - [ ] Eliminar debates em sala  
   - [ ] Reduzir interação humana

3. Qual aplicação da IA generativa pode ser considerada um risco?  
   - [ ] Criação de arte digital  
   - [ ] Apoio em programação  
   - [x] Produção de fake news  
   - [ ] Geração de resumos acadêmicos

---

### Quiz 3 – Conceitos Técnicos de IA

1. O que é um "modelo de linguagem"?  
   - [ ] Um banco de dados simples  
   - [ ] Um editor de texto  
   - [x] Um sistema treinado para prever e gerar linguagem humana  
   - [ ] Um dicionário digital

2. Qual técnica é usada para treinar IA generativa?  
   - [ ] Programação manual de regras  
   - [ ] Estatísticas básicas  
   - [x] Aprendizado profundo (Deep Learning)  
   - [ ] Planilhas Excel

3. O que significa "prompt engineering"?  
   - [ ] Criar algoritmos de busca  
   - [ ] Escrever código em Python  
   - [x] Elaborar instruções eficazes para guiar a IA  
   - [ ] Configurar hardware para IA

   ---

   ## 🤝 Como Contribuir
1. Faça um fork do projeto  
2. Crie uma branch para sua feature: `git checkout -b minha-feature`  
3. Commit suas alterações: `git commit -m 'Minha nova feature'`  
4. Faça push para a branch: `git push origin minha-feature`  
5. Abra um Pull Request  

---

## 📜 Licença
Este projeto está licenciado sob a LICENSE.  

---

