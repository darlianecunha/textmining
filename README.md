# PDFWords — Rede de Co-ocorrência para VOSviewer

**Ferramenta de análise bibliométrica e text mining que transforma PDFs em redes de co-ocorrência de palavras compatíveis com o VOSviewer.**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20708534.svg)](https://doi.org/10.5281/zenodo.20708534)

🔗 **Demo ao vivo:** [text-umber-delta.vercel.app](https://text-umber-delta.vercel.app)

---

## Sobre o projeto

O PDFWords permite carregar um ou mais arquivos PDF, extrair o texto localmente (sem envio a servidores), processar as palavras e gerar um arquivo JSON no formato aceito pelo [VOSviewer Online](https://app.vosviewer.com). Com esse arquivo, é possível visualizar mapas de co-ocorrência de palavras em segundos.

É especialmente útil para pesquisadores que realizam análises bibliométricas, revisões sistemáticas de literatura e estudos de text mining.

---

## Funcionalidades

- Carregamento de múltiplos PDFs por drag & drop ou seleção
- Extração de texto 100% local (sem envio de dados)
- Geração de rede de co-ocorrência de palavras no formato VOSviewer JSON
- Parâmetros configuráveis:
  - Frequência mínima de ocorrência
  - Co-ocorrência mínima entre termos
  - Número máximo de palavras na rede
  - Comprimento mínimo de caracteres por palavra
- Stopwords automáticas em português e inglês
- Stopwords personalizadas via interface
- Exportação do JSON para VOSviewer
- Exportação de frequências em CSV
- Abertura direta no VOSviewer Online
- Interface responsiva e acessível

---

## Como usar

1. Acesse [text-umber-delta.vercel.app](https://text-umber-delta.vercel.app)
2. Arraste seus PDFs para a área de upload (ou clique para selecionar)
3. Ajuste os parâmetros da rede conforme necessário
4. Clique em **Gerar rede de co-ocorrência**
5. Faça o download do JSON gerado
6. Abra [app.vosviewer.com](https://app.vosviewer.com), clique em **Open** → **VOSviewer JSON file** e carregue o arquivo

> **Atenção:** PDFs digitalizados (apenas imagem) precisam de OCR antes do processamento.

---

## Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML / CSS / JavaScript | Interface e lógica da aplicação |
| [PDF.js](https://mozilla.github.io/pdf.js/) (v3.11) | Extração de texto dos PDFs |
| [VOSviewer](https://www.vosviewer.com/) | Visualização da rede de co-ocorrência |
| [Vercel](https://vercel.com/) | Hospedagem e deploy contínuo |

---

## Privacidade

Todo o processamento ocorre no navegador do usuário. Nenhum arquivo ou dado é enviado a servidores externos.

---

## Como citar

> Cunha, D. R. (2026). PDFWords: bibliometric text-mining for VOSviewer co-occurrence networks (v0.1.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.20708534

---

## Autora

**Darliane Ribeiro Cunha, PhD**
Pesquisadora em governança de sustentabilidade, analytics ambiental e ODS
[ORCID: 0000-0003-2548-1237](https://orcid.org/0000-0003-2548-1237)

---

## Licença

Este projeto é de uso livre para fins acadêmicos e de pesquisa.
