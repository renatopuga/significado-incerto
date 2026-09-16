# Significado Incerto

> Um conto sobre reparo, risco e escolha.

**Significado Incerto** é um projeto literário de Renato David Puga que aproxima genética, hereditariedade e tomada de decisão de questões humanas como pertencimento, medo, cuidado e escolha.

Este repositório privado reúne o manuscrito, os materiais editoriais e o histórico de desenvolvimento da obra. Ele também documenta, de forma transparente, o uso de inteligência artificial na expansão textual do roteiro original.

## Estado do projeto

**Pré-publicação — 1.ª edição em preparação.**

Os campos editoriais ainda não definidos — como ISBN, editora, data de publicação e preço — estão identificados em [METADATA.yml](METADATA.yml) e no [checklist de publicação](publication/RELEASE_CHECKLIST.md).

## Autoria e uso de IA

- **Concepção, roteiro original, direção narrativa e autoria:** Renato David Puga.
- **Assistência de IA:** apoio à expansão textual, exploração de alternativas, revisão e organização.
- **Decisão editorial e responsabilidade final:** Renato David Puga.

A descrição completa do processo e seus limites está em [AI_ASSISTANCE.md](AI_ASSISTANCE.md).

## Estrutura do repositório

| Caminho | Conteúdo |
|---|---|
| `manuscript/` | Arquivos-fonte do manuscrito e orientações de versionamento |
| `assets/` | Capa, imagens e materiais gráficos autorizados |
| `publication/` | Checklist, arquivos finais e materiais para submissão/publicação |
| `METADATA.yml` | Metadados bibliográficos e editoriais |
| `CITATION.cff` | Forma recomendada de citar o projeto |
| `AI_ASSISTANCE.md` | Declaração de contribuição da IA |
| `CONTRIBUTING.md` | Política de contribuições e correções |
| `RIGHTS.md` | Direitos autorais e condições de uso |
| `CHANGELOG.md` | Histórico das versões editoriais |

## Organização recomendada dos arquivos

```text
significado-incerto/
├── manuscript/
│   ├── README.md
│   └── significado-incerto.md
├── assets/
│   └── README.md
├── publication/
│   └── RELEASE_CHECKLIST.md
├── README.md
├── METADATA.yml
├── CITATION.cff
├── AI_ASSISTANCE.md
├── CONTRIBUTING.md
├── RIGHTS.md
└── CHANGELOG.md
```

O arquivo principal do manuscrito deverá usar UTF-8 e Markdown, salvo se a versão editorial oficial for mantida em outro formato. PDFs, EPUBs e arquivos prontos para impressão devem ser tratados como artefatos de release, não como fonte primária.

## Versionamento

Versões de trabalho seguem `0.x`. A primeira edição publicada será marcada como `v1.0.0`. Cada release deverá registrar:

1. versão e data;
2. estado editorial do texto;
3. formatos incluídos;
4. identificadores bibliográficos;
5. checksum dos arquivos finais;
6. alterações relevantes desde a versão anterior.

## Citação

A forma recomendada está em [CITATION.cff](CITATION.cff). Enquanto a edição não possuir ISBN ou DOI, cite o autor, o título, a edição, o ano e a versão do repositório.

## Direitos

Copyright © 2026 Renato David Puga. Todos os direitos reservados.

O acesso a este repositório não concede licença para copiar, redistribuir, adaptar, treinar modelos ou publicar o texto. Consulte [RIGHTS.md](RIGHTS.md).
