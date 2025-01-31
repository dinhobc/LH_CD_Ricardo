📂 Estrutura do Repositório

Link do vídeo explicando o projeto: https://drive.google.com/file/d/1r-nw2HAOsmlxfPYOViDxoPXiKHGZaDUA/view?usp=drivesdk

notebooks/ - Contém notebooks com a análise exploratória dos dados (EDA) e modelagem.

models/ - Contém o modelo treinado salvo em formato .pkl.

requirements.txt - Lista de dependências necessárias para rodar o projeto.

README.md - Instruções sobre instalação e execução do projeto.

🚀 Instalação e Execução

Clone este repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

Crie um ambiente virtual (opcional, mas recomendado):
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows

Instale as dependências:
pip install -r requirements.txt

Execute o notebook para treinar e avaliar o modelo.

Para prever o preço de um imóvel, carregue o modelo salvo e passe os novos dados.

📊 Metodologia

Análise Exploratória de Dados (EDA): Exploração dos principais padrões nos dados.

Tratamento de Dados: Normalização e codificação de variáveis categóricas.

Modelagem: Modelo baseado em XGBoost para previsão de preços.

Avaliação: Métricas como MAE e RMSE foram utilizadas para medir o desempenho do modelo.

📌 Tecnologias Utilizadas

Python

Pandas, NumPy

Scikit-learn

XGBoost

Jupyter Notebook
