# Relatório Financial Sample no Power BI

Projeto prático do desafio de Power BI da DIO. O objetivo é replicar duas páginas criadas durante o curso com a sample financeira e criar, por conta própria, uma terceira página com mapas e gráfico de pizza.

## Dados

- Arquivo: [`dados/Financial Sample.xlsx`](dados/Financial%20Sample.xlsx)
- Origem: repositório do curso, [julianazanelatto/power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst)
- Conteúdo: 700 linhas com segmento, país, produto, unidades vendidas, vendas (Sales), lucro (Profit) e datas.

## Estrutura do repositório

```
dados/        base de dados usada no relatório
relatorio/    arquivo .pbix do projeto
evidencias/   prints das páginas do relatório
README.md     este documento
```

## Páginas do relatório

### Página 1 e Página 2 (replicadas do curso)

Replicação das duas primeiras páginas do relatório do curso, usando a mesma sample.

> TODO: descreva em 2 ou 3 linhas o que cada página mostra (por exemplo, quais gráficos, cartões e filtros você usou) e inclua os prints abaixo.

![Página 1](evidencias/pagina-1.png)
![Página 2](evidencias/pagina-2.png)

### Página 3 (criada por mim)

Página com três visuais:

| Visual | O que mostra | Como foi montado |
|---|---|---|
| Mapa: vendas e unidades por país | Soma de *Sales* e de *Units Sold* por país | País em Localização, Sales em Tamanho, Units Sold em Dicas de ferramenta |
| Mapa: lucro por país | Soma de *Profit* por país | País em Localização, Profit em Tamanho |
| Pizza: lucro por segmento | Soma de *Profit* por *Segment* | Segment em Legenda, Profit em Valores |

![Página 3](evidencias/pagina-3.png)

### Ajustes feitos

- Disposição dos visuais conferida e alinhada.
- Títulos renomeados para nomes claros e diretos.
- Campos das dicas de ferramentas revisados.

> TODO: ajuste esta lista para refletir o que você realmente fez.

## Publicação

- Relatório publicado: TODO (link, se tiver conta que permita publicar) ou "não publicado; arquivo .pbix disponível em `relatorio/`".
- Suplemento no PowerPoint: TODO ("não utilizado, pois não tenho PowerPoint; o projeto de Power BI foi salvo em `relatorio/`").

## Ferramentas

- Power BI Desktop
- GitHub

## O que aprendi

> TODO: escreva 2 ou 3 frases sobre o que você aprendeu (por exemplo, sobre criar mapas, escolher visuais e configurar dicas de ferramentas).
