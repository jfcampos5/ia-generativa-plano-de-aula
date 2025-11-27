
## 🔄 Automação com GitHub Actions
Este projeto inclui um workflow para:
- ✅ Validar arquivos Markdown (README.md)
- ✅ Converter a apresentação (.pptx) para PDF automaticamente

### Como funciona:
1. Ao fazer push para a branch `main`, o GitHub Actions executa:
   - Validação do Markdown usando markdownlint
   - Conversão da apresentação para PDF usando LibreOffice

### Estrutura:
- `.github/workflows/main.yml` → Workflow principal
- `.markdownlint.json` → Configuração de validação Markdown

### Benefícios:
- Garantia de qualidade na documentação
- Automação da geração de PDF para compartilhamento
