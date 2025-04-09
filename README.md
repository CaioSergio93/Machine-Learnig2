Projeto de Machine Learning - Classificação de Diabetes

📌 Visão Geral
Este projeto implementa um modelo de Machine Learning para classificação binária usando o dataset Pima Indians Diabetes Database do Kaggle. O objetivo é prever se um paciente tem diabetes com base em características como nível de glicose, pressão sanguínea, índice de massa corporal (BMI), entre outros.

📋 Dataset
Fonte: Kaggle - Pima Indians Diabetes Database

Variáveis:

Pregnancies: Número de vezes que engravidou

Glucose: Concentração de glicose no sangue

BloodPressure: Pressão arterial (mm Hg)

SkinThickness: Espessura da dobra cutânea do tríceps (mm)

Insulin: Nível de insulina (mu U/ml)

BMI: Índice de massa corporal (peso em kg / (altura em m)²)

DiabetesPedigreeFunction: Função que avalia risco genético de diabetes

Age: Idade (anos)

Outcome (Target): 0 = Não diabético | 1 = Diabético

⚙️ Configuração do Ambiente
Pré-requisitos
Python 3.8+

Bibliotecas listadas em requirements.txt

Instalação
Clone o repositório:

git clone https://github.com/CaioSergio93/Machine-Learnig2.git

Crie e ative um ambiente virtual (recomendado):

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Instale as dependências:


pip install -r requirements.txt

🚀 Como Executar
Execute o script principal:

python scripts/train_model.py
Saída esperada:

Análise exploratória dos dados (gráficos)

Métricas de avaliação (Acurácia, Precisão, Recall, F1-Score, AUC-ROC)

Matriz de confusão e curva ROC

📈 Métricas de Desempenho
O modelo de Regressão Logística obteve os seguintes resultados:

Métrica	Valor
Acurácia	~0.75
Precisão	~0.70
Recall	~0.60
F1-Score	~0.65
AUC-ROC	~0.80

🛠 Melhorias Futuras
Testar outros algoritmos (Random Forest, XGBoost)

Balanceamento de classes (SMOTE, Class Weights)

Otimização de hiperparâmetros (GridSearchCV)

Deploy do modelo em uma API (FastAPI/Flask)

📄 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

🤝 Contribuição
Contribuições são bem-vindas! Siga os passos:

Faça um fork do projeto

Crie uma branch (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m 'Adiciona nova feature')

Push para a branch (git push origin feature/nova-feature)

Abra um Pull Request

Desenvolvido por [Caio Sérgio] | [2025]
📧 Contato: caio.dev.system@gmail.com

🎯 Objetivo Final
Este projeto serve como base para sistemas de auxílio médico na detecção precoce de diabetes, podendo ser integrado a aplicações de saúde digital.
