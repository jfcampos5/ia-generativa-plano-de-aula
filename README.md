# 📘 Desafio de Projeto – Plano de Aula Interativo e Personalizado com Ecossistema IA

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue) ![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![CI](https://github.com/jfcampos5/Plano-de-aula-interativo-IA-/actions/workflows/main.yml/badge.svg)
![Último Commit](https://img.shields.io/github/last-commit/jfcampos5/Plano-de-aula-interativo-IA-)
![Markdown Lint](https://img.shields.io/badge/Markdown-Lint-success)

---
## Índice
1. [Sobre o projeto](#sobre-o-projeto)
2. [Objetivos de aprendizagem](#objetivos-de-aprendizagem)
3. [Estrutura do repositório](#estrutura-do-repositorio)
4. [Plano de aula](#plano-de-aula)
5. [Materiais complementares](#materiais-complementares)
6. [Como publicar no GitHub pages](#como-publicar-no-github-pages)
7. [Quiz interativo online](#quiz-interativo-online)
8. [Automação com GitHub Actions](#automacao-com-github-actions)
9. [Boas práticas de manutenção](#boas-praticas-de-manutencao)
10. [Recursos úteis](#recursos-uteis)
11. [Entrega](#entrega)
12. [Conclusão](#conclusao)
13. [Como contribuir](#como-contribuir)
14. [Licença](#licenca)

---

## Sobre o Projeto
Este projeto tem como objetivo **criar um Plano de Aula Interativo e Personalizado com Ecossistema IA**, aplicando conceitos de Inteligência Artificial em um contexto educacional.  
A documentação é organizada para servir como **portfólio** e **referência prática**.

---

## Objetivos de Aprendizagem
- Compreender conceitos básicos de IA generativa  
- Explorar aplicações práticas em diferentes áreas  
- Desenvolver senso crítico sobre ética e segurança na IA  
- Criar conteúdo interativo com ferramentas de IA  
- Documentar e compartilhar conhecimento no GitHub  

---

## Estrutura do Repositório
```plaintext
plano-aula-ia/
├── README.md                  # Documentação principal
├── .markdownlint.json         # Configuração para validação Markdown
├── .github/workflows/main.yml # Workflow de automação
├── images/                    # Capturas de tela e diagramas
├── docs/                      # Materiais complementares e site para GitHub Pages
└── quizzes/                   # Arquivos do quiz interativo
```

---

## Plano de Aula
**Tema:** Introdução à IA Generativa  
**Objetivo:** Apresentar conceitos básicos e demonstrar aplicações práticas.  

**Conteúdo Programático:**  
1. O que é IA generativa  
2. Principais modelos e aplicações  
3. Demonstração prática com Copilot / ChatGPT  
4. Ética e segurança  

**Metodologia:**  
- Exposição dialogada  
- Atividade prática: criação de prompts  
- Debate sobre riscos e benefícios  
- Registro no GitHub  

**Recursos:**  
- Slides  
- Ferramentas de IA (Copilot, ChatGPT, DIO Labs)  
- GitHub para documentação  
- Quizzes interativos  

---


## Materiais Complementares
Este repositório inclui recursos adicionais para apoiar o plano de aula:

### Slides e Documentos
- docs/Plano_de_Aula_IA_Generativa.odp – Slide do plano de aula


### Imagens
- Diagramas e fluxogramas disponíveis na pasta `images/`

---

## Como Publicar no GitHub Pages
1. Crie a pasta `docs/` e coloque os arquivos HTML do projeto nela.  
2. Vá em **Settings > Pages** no repositório.  
3. Em **Source**, selecione a branch `main` e a pasta `/docs`.  
4. Salve e aguarde a publicação.  
5. Acesse pelo link:  
   `https://<seu-usuario>.github.io/<nome-do-repo>/`.  

---

## Quiz Interativo Online
Acesse o quiz diretamente pelo GitHub Pages:  
👉 **https://jfcampos5.github.io/ia-generativa-plano-de-aula/**  

**Funcionalidades:**  
- ✅ Feedback visual imediato (respostas corretas/erradas)  
- ✅ Controle de tempo por questão  
- ✅ Exibição da pontuação final  
- ✅ Botão para reiniciar o quiz  

**Como rodar localmente:**  
```bash
cd quizzes
open index.html
```

---

## Automação com GitHub Actions
- Validação do Markdown com **markdownlint**  
- Conversão automática de apresentações para PDF  
- Workflow: `.github/workflows/main.yml`  

---

## Boas Práticas de Manutenção
- Mantenha o README atualizado  
- Use **issues** para registrar melhorias  
- Padronize nomes de arquivos e pastas  
- Valide Markdown antes do commit  

---

## Recursos Úteis
- https://www.markdownguide.org/basic-syntax/  
- https://docs.github.com/en/pages  
- https://www.dio.me  

---

## Entrega
Este repositório contém:  
- Um arquivo **README.md** detalhado  
- Estrutura organizada para documentação  
- Workflow de automação com GitHub Actions  
- Quiz interativo publicado no GitHub Pages  

---

## Conclusão
Este projeto demonstra como aplicar **IA e boas práticas de documentação** em um plano de aula interativo.  
Além de atender ao desafio da DIO, serve como portfólio para destacar habilidades técnicas e de comunicação.

---

## Como Contribuir
1. Faça um fork  
2. Crie uma branch: `git checkout -b minha-feature`  
3. Commit: `git commit -m 'Minha nova feature'`  
4. Push: `git push origin minha-feature`  
5. Abra um Pull Request  

---

## Licença
Este projeto está licenciado sob a MIT License.  
