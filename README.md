#  EXPLAINABLE AI (XAI):  Tornando Modelos de IA Explicáveis com LIME
Nome: Leticia Santana Novais - Gestão da Tecnologia da Informação - UniFECAF
## Contexto
Uma empresa utiliza modelos preditivos para análise de crédito bancário, apesar da boa precisão surgiram questionamentos sobre o motivo das decisões, principalmente quando o crédito é negado. O objetivo deste trabalho foi aplicar técnicas de Explainable AI para tornar as previsões mais transparentes.
## Modelo Utilizado
Foi desenvolvido um modelo de classificação utilizando o algoritmo Random Forest e treinado com o dataset German Credit que contém informações financeiras fictícias de clientes, assim o modelo aprendeu a prever se um cliente representa bom ou mau risco de crédito.
## Explicações Geradas pelo LIME
Após o treinamento, foi utilizada a biblioteca LIME para explicar previsões individuais, quando um cliente é selecionado o LIME mostra apenas como o modelo chegou na decisão daquele caso específico e não como ele funciona para todos os clientes.
## Reflexões e Limitações
A aplicação do LIME mostrou a importância da interpretabilidade em modelos de IA, principalmente em contextos como análise de crédito em que decisões precisam de justificativas.
As explicações representam apenas a lógica do modelo para um caso específico e não o funcionamento completo do algoritmo, mas mesmo com essa limitação elas contribuem para aumentar a transparência e compreensão do comportamento do modelo.
## Dados Utilizados
Carreguei o dataset German Credit Data direto do openml, é o mesmo dataset que está disponível na UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data
## Como Executar
Instale as dependências abaixo e execute o notebook no Google Colab
- pandas
- numpy
- scikit-learn
- lime
