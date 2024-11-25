Sivida Neural Model

Este projeto implementa um sistema de monitoramento ambiental que coleta, processa e analisa dados simulados para prever a qualidade do ar. Utiliza aprendizado de máquina e redes neurais para análise e visualização dos resultados.

📖 Descrição do Projeto

O Sivida Neural Model realiza as seguintes tarefas:
- Coleta dados ambientais simulados (temperatura, umidade, CO2, TVOC e qualidade do ar).
- Armazena os dados em um banco de dados SQLite.
- Limpa os dados e remove outliers utilizando o método IQR.
- Treina um modelo LSTM para prever a qualidade do ar.
- Visualiza resultados através de gráficos, matriz de confusão e relatórios de desempenho.

🚀 Instalação

1. Clone o repositório:
   git clone <https://github.com/WillianRullian/SIVIDA>
   cd <SIVIDA>

2. Instale as dependências (recomenda-se usar um ambiente virtual):
   pip install -r requirements.txt

▶️ Como Executar

1. Execute o script principal:
   python sividaneuralmodel_1_7.py

2. O script realizará as seguintes etapas:
   - Coleta e armazenamento de dados ambientais simulados no banco de dados.
   - Limpeza e pré-processamento dos dados.
   - Treinamento e avaliação do modelo LSTM.
   - Geração de gráficos e relatórios.

3. Os resultados incluem:
   - Gráficos de acurácia e validação.
   - Matriz de confusão.
   - Relatórios de classificação e métricas como AUC-ROC.

📂 Estrutura do Projeto

/
├── sividaneuralmodel_1_7.py   # Script principal do projeto
└── requirements.txt           # Arquivo com as dependências do projet 

🛠️ Tecnologias Utilizadas

- Python 3.8+
- Manipulação de Dados: Pandas, Numpy
- Visualização: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, TensorFlow/Keras
- Banco de Dados: SQLite

