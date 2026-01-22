# CMS IX Radiologia

Este repositório é o **CMS de conhecimento** da IX Radiologia, utilizado como base de dados para o assistente virtual.

## Finalidade

Os arquivos Markdown contidos neste repositório são consumidos via HTTP por sistemas externos (n8n + IA) para fornecer informações aos pacientes.

## Estrutura

- `base/` — Informações gerais e respostas especiais
- `exames/` — Arquivos individuais por exame
- `convenios/` — Arquivos individuais por convênio
- `templates/` — Modelos para criação de novos arquivos

## Importante

**Este repositório contém APENAS documentação operacional.**

NÃO devem ser colocados aqui:
- Regras de negócio
- Protocolos internos
- Fluxos de trabalho
- Código fonte
