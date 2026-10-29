# AI Documentation Generator

Laboratório local-first para gerar documentos de gestão de projetos (termo de abertura, requisitos, cronograma, orçamento e riscos) com modelos de linguagem executados localmente.

## Problema

Documentos de projeto costumam ser escritos do zero a cada vez, sem padrão, e podem conter informações sensíveis de clientes e de negócio. Este projeto testa um fluxo que gera esses documentos a partir de dados básicos do projeto, usando modelos locais para que os dados não saiam da máquina.

## Stack

- Python
- LLMs locais
- Engenharia de prompts
- Templates de documento

## Como rodar

O código-fonte é privado, por causa dos dados e dos prompts usados. Por isso, este repositório não contém a aplicação para executar.

O conteúdo publicado é a documentação do projeto: conceito, fluxo, objetivos e aprendizados.

## Estrutura

```text
├── assets/
│   └── projects/   imagem de capa do projeto
└── docs/
    └── ai-documentation-generator.md   documentação do projeto
```

## Fluxo

```text
Dados do projeto → prompt estruturado → modelo local → conteúdo gerado → template → documento final
```

## Status

Laboratório privado e local. O foco atual é melhorar os templates, refinar os prompts, testar os fluxos com modelos locais e estruturar melhor os dados de entrada.

## Próximos passos

- Melhorar a consistência entre os documentos gerados.
- Criar uma forma de pré-visualizar o documento antes da geração.
- Exportar para DOCX e PDF.
- Separar a configuração sensível da versão pública, caso o projeto ganhe uma demonstração.
