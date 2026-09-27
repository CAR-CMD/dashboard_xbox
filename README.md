# Dashboard de Vendas Xbox

Dashboard desenvolvido em Excel para organizar e analisar dados de vendas de assinaturas relacionadas ao Xbox Game Pass, EA Play e Minecraft. A visualização reúne informações para apoiar a leitura do desempenho das assinaturas e a tomada de decisões baseada em dados.

## Arquivo

- `dashboard_xbox.xlsx`: pasta de trabalho com a base de dados, cálculos e dashboard.

## Organização da pasta de trabalho

- **Bases**: tabela com 295 registros de assinaturas e campos como plano, datas, renovação automática, tipo de assinatura, complementos e valor total.
- **Cálculos**: tabelas dinâmicas de apoio conectadas ao tipo de assinatura.
- **Dashboard**: painel de vendas/assinaturas do Xbox Game Pass, EA Play Season Pass e Minecraft Season Pass.
- **Assets**: referências visuais e paleta de cores utilizadas no arquivo.

## Como reproduzir

1. Abra `dashboard_xbox.xlsx` no Microsoft Excel.
2. Para atualizar a análise após alterar a base, use **Dados > Atualizar Tudo**.
3. Use os filtros e segmentações disponíveis na pasta de trabalho para explorar os tipos de assinatura.

As tabelas dinâmicas, segmentações e fórmulas do dashboard foram preparadas para uso no Excel. Outros aplicativos de planilha podem apresentar diferenças de compatibilidade.

## Dados e privacidade

O arquivo contém dados de assinantes, incluindo nomes e identificadores. Confirme que você tem autorização para compartilhar esses dados antes de publicar o repositório. Se necessário, anonimize os registros e valide o dashboard com a versão anonimizada.

## Estrutura do repositório

```text
dashboard_xbox/
├── README.md
├── .gitignore
└── dashboard_xbox.xlsx
```