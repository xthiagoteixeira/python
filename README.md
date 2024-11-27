WDO Analysis Suite
Este conjunto de scripts oferece uma análise abrangente e multifacetada do mercado de mini contratos de dólar (WDO), utilizando dados da B3 e outras fontes. Cada script é projetado para realizar tarefas específicas, desde a coleta de dados até análises preditivas avançadas.
Scripts Incluídos
1. WDO Analise TV_v16.ipynb
Este script realiza uma análise detalhada dos dados do WDO utilizando dados do TradingView.
Benefícios:

Identificação precisa de níveis de suporte e resistência
Análise de volume e liquidez
Cálculo de indicadores técnicos avançados
Geração de relatórios detalhados

Tecnologias utilizadas:

pandas, numpy para manipulação de dados
sklearn para pré-processamento
TensorFlow para modelagem preditiva
Matplotlib e Seaborn para visualizações

2. WDO Coleta B3_v5.ipynb
Script dedicado à coleta automática de dados históricos do WDO diretamente da B3.
Benefícios:

Coleta automatizada de dados históricos
Tratamento e limpeza de dados brutos
Armazenamento eficiente de dados em formato CSV

Tecnologias utilizadas:

Selenium para web scraping
pandas para processamento de dados
Logging para registro de atividades

3. WDO Coleta MT.ipynb
Este script coleta dados do WDO através da plataforma MetaTrader.
Benefícios:

Acesso a dados em tempo real
Coleta de múltiplos timeframes
Integração direta com a plataforma de trading

Tecnologias utilizadas:

MetaTrader5 API
pandas para organização de dados
Logging para monitoramento de execução

4. WDO Analise MT_v7.ipynb
Realiza uma análise aprofundada dos dados coletados via MetaTrader.
Benefícios:

Análise técnica avançada
Identificação de padrões de mercado
Previsão de movimentos futuros

Tecnologias utilizadas:

TensorFlow para modelagem preditiva
pandas e numpy para análise de dados
ta-lib para indicadores técnicos avançados

5. WDO Analise B3_v3.ipynb
Este script foca na análise dos dados coletados diretamente da B3.
Benefícios:

Análise fundamentada em dados oficiais da bolsa
Identificação de níveis importantes baseados em volume
Geração de relatórios para a próxima sessão de mercado

Tecnologias utilizadas:

pandas e numpy para processamento de dados
sklearn para análise estatística
Matplotlib para visualizações

Vantagens Gerais da Suite

Análise Abrangente: Combina diferentes fontes e métodos de análise para uma visão completa do mercado.
Automação: Reduz significativamente o tempo gasto em coleta e processamento manual de dados.
Precisão: Utiliza técnicas avançadas de machine learning para identificação de padrões e previsões.
Flexibilidade: Permite análises em diferentes timeframes e perspectivas de mercado.
Tomada de Decisão Informada: Fornece insights valiosos para traders e analistas de mercado.

Requisitos

Python 3.7+
Bibliotecas: pandas, numpy, sklearn, TensorFlow, MetaTrader5, Selenium, ta-lib
Acesso às plataformas: TradingView, MetaTrader, B3

Instalação
bashCopypip install -r requirements.txt

6. Coletor de Dados de FIIs
Este script Python automatiza a coleta de dados de Fundos de Investimento Imobiliário (FIIs) do site fiis.com.br,
processando e organizando as informações em um formato facilmente analisável.

Descrição
O script utiliza web scraping para extrair dados detalhados sobre FIIs de uma fonte confiável,
processa essas informações e as exporta para um arquivo Excel, facilitando análises posteriores.

Benefícios

Automação da Coleta de Dados: Elimina a necessidade de coleta manual, economizando tempo e reduzindo erros.
Dados Atualizados: Captura as informações mais recentes disponíveis no site.
Organização Estruturada: Formata os dados de maneira consistente e organizada.
Fácil Análise: Exporta para Excel, permitindo análises imediatas e visualizações.
Ampla Gama de Informações: Coleta diversos indicadores importantes para análise de FIIs.

Tecnologias Utilizadas

Selenium: Para automação de navegador e web scraping.
Pandas: Para manipulação e processamento eficiente dos dados.
Chrome WebDriver: Para interação com o navegador Chrome.

Funcionalidades

Acessa automaticamente o site fiis.com.br.
Extrai dados da tabela de FIIs.
Processa e limpa os dados coletados.
Converte valores para formatos numéricos apropriados.
Exporta os dados para um arquivo Excel.

Requisitos

Python 3.x
Selenium
Pandas
Chrome WebDriver

Instalação
bashCopypip install selenium pandas
Certifique-se de ter o Chrome WebDriver instalado e configurado no seu PATH.
Uso

Execute o script em um ambiente Jupyter Notebook ou Python.
O script acessará automaticamente o site e coletará os dados.
Após a execução, um arquivo Excel será gerado no caminho especificado.

Personalização
Você pode modificar o caminho de saída do arquivo Excel alterando a linha:
pythonCopydados.to_excel(r'C:\ARQUIVOS\OneDrive\Bolsa\Analise\export_fiis.xlsx', index=None)


Uso
Cada script pode ser executado individualmente através de um ambiente Jupyter Notebook. Certifique-se de configurar corretamente as credenciais e caminhos de arquivo antes da execução.

Contribuições
Contribuições são bem-vindas! Por favor, leia o guia de contribuição antes de submeter pull requests.
