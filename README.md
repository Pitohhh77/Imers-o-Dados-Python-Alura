### 📊 Dashboard Interativo de Salários na Área de Dados

Bem-vindo ao **Dashboard de Salários na Área de Dados**! Esta aplicação web, desenvolvida com Python, `Streamlit` e `Plotly`, permite explorar e analisar o cenário salarial do mercado de dados de forma interativa e visualmente atraente.

O objetivo do projeto é fornecer uma ferramenta intuitiva para profissionais, estudantes e recrutadores entenderem as tendências salariais, as diferenças entre cargos e o impacto de fatores como senioridade e localização.

---

### ✨ Destaques do Dashboard

#### **1. Filtros Dinâmicos na Barra Lateral**

À esquerda, você encontra uma série de filtros poderosos para personalizar sua análise:

* **Ano:** Compare a evolução salarial ao longo do tempo.
* **Senioridade:** Veja como os salários variam entre níveis (Júnior, Pleno, Sênior, etc.).
* **Tipo de Contrato:** Analise o impacto de diferentes regimes de trabalho (CLT, PJ, etc.).
* **Tamanho da Empresa:** Descubra se o porte da empresa influencia a remuneração.

#### **2. Métricas e KPIs de Alto Nível**

Na parte superior do painel principal, quatro cartões de métricas fornecem uma visão geral instantânea:

* **Salário Médio:** A média salarial anual em USD.
* **Salário Máximo:** O maior salário registrado no conjunto de dados.
* **Total de Registros:** O volume de dados na sua seleção atual.
* **Cargo Mais Frequente:** O cargo mais comum na sua busca.

#### **3. Visualizações de Dados que Contam uma História**

Explore a seção de gráficos para obter insights aprofundados:

* **Top 10 Cargos:** Gráfico de barras que exibe os cargos com as maiores médias salariais.
* **Distribuição Salarial:** Histograma que mostra a concentração de salários por faixa de valor.
* **Proporção de Trabalho:** Gráfico de rosca que ilustra a popularidade de modelos de trabalho (remoto, híbrido, presencial).
* **Mapa de Salários por País:** Um mapa-múndi que visualiza a média salarial para o cargo de Engenheiro de Dados em diferentes localizações.

---

### ⚙️ Como Rodar o Projeto Localmente

Para ter o dashboard funcionando em sua máquina, siga estes passos simples:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/vqrca/dashboard_salarios_dados.git](https://github.com/vqrca/dashboard_salarios_dados.git)
    cd dashboard_salarios_dados
    ```
2.  **Instale as bibliotecas necessárias:**
    ```bash
    pip install streamlit pandas plotly
    ```
3.  **Execute o aplicativo:**
    ```bash
    streamlit run seu_script.py
    ```
    (Substitua `seu_script.py` pelo nome do seu arquivo Python principal)

Seu navegador abrirá automaticamente o dashboard. Se isso não acontecer, copie a URL fornecida no terminal (`http://localhost:8501`) e cole na barra de endereços.

---

### 🛠️ Estrutura do Código

O projeto está contido em um único script Python, que é fácil de entender e modificar. A lógica é organizada em seções claras, desde o carregamento dos dados até a renderização dos gráficos e tabelas.

---

### 🤝 Contribuições

Sua contribuição é muito bem-vinda! Se tiver sugestões, ideias de melhorias ou quiser reportar um bug, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.
