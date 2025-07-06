# Análise Exploratória de Dados - Bootcamp de Ciência de Dados AVANTI

Este repositório documenta nosso projeto de análise exploratória de dados, desenvolvido durante o Bootcamp de Ciência de Dados da AVANTI. O principal objetivo foi analizar um dataset para descobrir padrões, tendências e anomalias, extraindo insights que possam extrair futuras análises ou decisões.

---

### Autores

Este projeto é o resultado da colaboração de um grupo de estudantes do Bootcamp de Ciência de Dados da AVANTI, sob a orientação do professor Madson Luiz Dantas Dias.

* Fernando da Conceição Cordeiro Filho
* David William A. Oliveira
* José Vitor Paulino Delmiro
* Maria Eduarda Justino

---

### Sobre o Projeto

A Análise Exploratória de Dados (AED) é um passo essencial em qualquer projeto de dados, e neste notebook, o `Bootcamp_Avanti.ipynb`, aplicamos suas principais técnicas. Em vez de pular direto para a modelagem, nós dedicamos tempo para realmente entender a história que os dados contam.

Nosso percurso, documentado no notebook, seguiu as seguintes etapas:

* **Inspeção e Preparação:** Começamos carregando os dados e fazendo uma primeira verificação de sua estrutura, tratando valores ausentes, corrigindo inconsistências e garantindo a qualidade para a análise.
* **Análise Descritiva:** Calculamos as principais métricas estatísticas para ter uma visão geral dos dados, tanto para as variáveis numéricas quanto para as categóricas.
* **Visualização de Dados:** Usamos uma variedade de gráficos — como histogramas, box plots e mapas de calor — para visualizar as distribuições e as relações entre as variáveis de forma intuitiva.
* **Identificação de Outliers e Correlações:** Investigamos a presença de valores atípicos e analisamos as correlações para entender como as variáveis se influenciam mutuamente.

Todo esse processo cria uma base robusta e confiável para qualquer etapa futura, como a construção de modelos preditivos.

---

### Tecnologias Utilizadas

Para desenvolver este projeto, utilizamos um conjunto de ferramentas padrão em Ciência de Dados:

* **Python 3.x**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

### Como Usar

Para fazer a análise pelo Google Colab apenas acesse o link abaixo

Para replicar esta análise em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SAGIEV007/Bootcamp-Avanti.git](https://SAGIEV007/Bootcamp-Avanti.git)
    cd Bootcamp-Avanti
    ```

2.  **Crie um ambiente virtual (opcional, mas recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3.  **Instale as dependências necessárias:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook Bootcamp_Avanti.ipynb
    ```
    O comando iniciará o servidor Jupyter e abrirá o notebook no seu navegador. A partir daí, basta executar as células em sequência para acompanhar toda a análise.

---

### Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.
