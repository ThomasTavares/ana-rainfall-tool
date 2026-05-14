## Clique na *badge* abaixo para executar a ferramenta
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ThomasTavares/ana-rainfall-tool/main?urlpath=voila%2Frender%2Fana-rainfall-tool.ipynb)

---
# ANA Rainfall Tool
Uma ferramenta interativa desenvolvida em Python para o processamento automatizado e análise estatística de séries históricas de precipitação oriundas da Agência Nacional de Águas (ANA). A aplicação utiliza a biblioteca `ipywidgets` para fornecer uma interface gráfica operada inteiramente via navegador, eliminando a necessidade de interação direta com o código-fonte.

## Funcionalidades
- **Processamento de Arquivos:** Leitura e interpretação direta de arquivos CSV no formato padrão exportado pelo portal HidroWeb da ANA.
- **Recorte Temporal:** Capacidade de processar a série histórica completa ou definir intervalos específicos de anos para a análise.
- **Controle de Qualidade:** Definição de limiares de tolerância baseados no número mínimo de dias com registros válidos por mês.
- **Estatísticas Dinâmicas:** Cálculo parametrizável de métricas como Média, Desvio Padrão, Mediana, Mínimo, Máximo e contagem de dias com chuva para diferentes limiares (>0mm, >10mm, >25mm, >50mm).
- **Resolução de Conflitos:** Tratamento automatizado de sobreposição de dados, priorizando dados consistidos sobre dados brutos.
- **Exportação Avançada:** Geração de arquivos Excel (`.xlsx`) estruturados em múltiplas abas (Dados Completos, Mensal por Ano, Histórico Mensal e Histórico Anual), contendo formatação condicional de cores para distinguir a origem do dado (Bruto vs. Consistido).

## Como Executar
A maneira mais simples de utilizar a ferramenta é executá-la diretamente no seu navegador, sem a necessidade de instalar Python ou qualquer biblioteca localmente.

1. Clique na *badge* do **Binder** no topo deste README.
2. Aguarde o provisionamento do ambiente (este processo pode levar alguns minutos).
3. A interface gráfica da ferramenta será carregada automaticamente na sua tela, pronta para o upload dos arquivos .csv.
