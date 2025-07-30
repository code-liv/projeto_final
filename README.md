📊 Projeto Final - Análise de Dados do Varejo Pernambucano
Este repositório contém o projeto final desenvolvido como parte do Trabalho de Conclusão de Curso da formação em Análise de Dados oferecida pela Telós & Neurotech.

📌 Sobre o Projeto
O projeto tem como objetivo a análise dos dados de um varejo localizado no estado de Pernambuco, que comercializa produtos como alimentos, itens para o lar, materiais de higiene e limpeza, entre outros. O varejo está presente em várias cidades do estado, e os dados analisados dizem respeito a compras, cadastro de clientes, campanhas de marketing e reclamações.

🧠 Objetivos
Realizar uma análise exploratória dos dados (EDA);

Tratar e limpar dados inconsistentes;

Criar variáveis úteis para análise;

Realizar agregações para entender o comportamento dos clientes;

Identificar padrões de consumo, reclamações e conversão em campanhas;

Gerar visualizações para apoiar tomadas de decisão;

Unificar todas as informações em um dataset final para uso em dashboards (Power BI).

🗂️ Conjuntos de Dados Utilizados
COMPRAS.xlsx: Histórico de compras dos clientes;

CADASTRAL.xlsx: Informações demográficas e de cadastro dos clientes;

CAMPANHAS.xlsx: Registro de campanhas de marketing, interações e conversões;

RECLAMACOES.xlsx: Detalhes sobre as reclamações realizadas pelos clientes.

🔧 Principais Etapas
1. Importação e Análise Exploratória (EDA)
Verificação de tipos de dados, valores nulos, datas inconsistentes e distribuição de colunas;

Exploração de campos como status de entrega, faixa etária, score inicial, canais de campanha etc.

2. Tratamento de Dados
Remoção de valores nulos e inconsistentes;

Conversão de tipos (ex: valor_compra para float);

Exclusão de datas futuras ou inválidas;

Criação de colunas booleanas (sexo_bool, converteu_em_compra_bool, etc.).

3. Criação de Variáveis
Agrupamento de métricas como:

Total gasto por cliente;

Quantidade de compras;

Parcelamento;

Taxa de conversão por canal;

Reclamações por cliente.

4. Visualizações Criadas
Distribuição de clientes por faixa etária;

Status de entrega (gráfico de pizza);

Taxa de conversão por canal de campanha (com paleta personalizada);

Funil de marketing (enviados, abertos, clicados, convertidos);

Distribuição do score inicial;

Boxplot comparando score entre clientes ativos e inativos.

5. Unificação de Dados
Todos os dados tratados foram unidos em um único DataFrame (df_unificado) e exportados para um .csv, pronto para visualização em Power BI.

📈 Ferramentas Utilizadas
Python (Pandas, NumPy, Seaborn, Matplotlib)

Google Colab

Excel

Power BI (para visualização final)

📎 Resultado Final
Arquivo final exportado: df_unificado_para_powerbi.csv

Visualizações ricas e informativas para apoio à tomada de decisão;

Análises que ajudam a entender o perfil dos clientes, a efetividade das campanhas e pontos críticos como canais de reclamação e satisfação.

👩‍💻 Autoria
Projeto desenvolvido por Lívia de Santana Pessôa como parte da formação em Análise de Dados da Telós & Neurotech.
