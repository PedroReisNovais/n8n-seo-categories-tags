# Automação de Categorias e Tags SEO no n8n

Template de fluxo para padronizar categorias e tags de conteúdo no WordPress a partir de uma fonte de planejamento em planilha.

## Problema resolvido

Categorias e tags inconsistentes prejudicam a organização editorial e a navegação de um blog. O fluxo consulta dados planejados, verifica a estrutura existente no WordPress e registra o resultado para acompanhamento.

## Fluxo

```text
Agendamento ou execução manual
  -> Google Sheets: leitura de categorias e tags
  -> WordPress: consulta ou criação de categorias
  -> WordPress: consulta ou criação de tags
  -> Google Sheets: atualização do resultado
```

## Tecnologias e integrações

- n8n
- Google Sheets
- WordPress REST API
- HTTP Request
- Agendamento e tratamento de dados

## Como importar

1. Importe `workflow.template.json` no n8n.
2. Crie credenciais próprias para Google Sheets e WordPress.
3. Substitua os campos `REPLACE_WITH_*` e URLs `example.invalid`.
4. Teste com um site e uma planilha de desenvolvimento antes de ativar o agendamento.

## Segurança e escopo

O arquivo é uma versão sanitizada para estudo e portfólio. Não contém credenciais, IDs de documentos, endpoints privados ou dados de clientes.

