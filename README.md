* ## **Descrição:**
* **Desafio:** Análise de Vendas de Jogos de Videogames
  * **Objetivo:**
    Os participantes devem consultar e analisar dados de vendas de jogos de videogames a partir do repositório disponível no Kaggle. O objetivo é criar um pipeline que permita explorar insights sobre as tendências de vendas, plataformas mais populares, e o desempenho de jogos ao longo dos anos.

* **Instruções:**
  * **Fonte de Dados:**
    Utilize o conjunto de dados disponível em [Kaggle: Vendas de Jogos de Videogames](https://www.kaggle.com/code/lusfernandotorres/vendas-de-jogos-de-videogames/input). 
  * **Tarefas:** 
    * **Consulta e Ingestão:** 
      * Baixar o conjunto de dados; 
      * Carregar os dados em um DataFrame utilizando Pandas. 
    * **Exploração Inicial:** 
      * Visualizar a estrutura dos dados e realizar uma análise exploratória (EDA) para entender as colunas e o tipo de dados.
    * **Limpeza dos Dados:** 
      * Identificar e tratar valores ausentes; 
      * Remover duplicatas; 
      * Corrigir eventuais inconsistências 
    * **Análise de Tendências:** 
      * Identificar as principais plataformas, 
      * Gêneros de jogos mais vendidos, 
      * Evolução das vendas ao longo dos anos. 
    * **Visualização:** 
      * Criar gráficos que mostrem as tendências de vendas;
      * O desempenho por plataforma;
      * Outros insights relevantes. 
  * **Entrega:** 
    * Um notebook Python (Jupyter Notebook) documentado com a análise, código e visualizações; 
    * Uma breve apresentação (slides ou documento) destacando os principais insights descobertos.
  **Extras (Opcional):**
    * Implementar uma previsão simples para vendas futuras usando um modelo de regressão linear ou outro algoritmo de aprendizado de máquina. 
    * Publicar a análise em um repositório no GitHub com README explicativo.

* ## **Desenvolvimento:**

* ### **Criando ambiente virtual:**
```bash
# game_analysis já considerado no .gitignore
python3 -m venv game_analysis && source game_analysis/bin/activate
```

* ### **Instalando dependências:**
```bash
pip install -r requirements.txt
```
