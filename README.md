
# 🧠 Detecção de Doença Renal Crônica com Machine Learning

Este repositório contém os arquivos relacionados à minha pesquisa de Iniciação Científica desenvolvida durante a graduação, cujo objetivo foi aplicar técnicas de *Machine Learning* para a detecção precoce de **Doença Renal Crônica (DRC)** com base em dados clínicos.

## 📄 Descrição do Projeto

A Doença Renal Crônica é uma condição silenciosa que, se não diagnosticada a tempo, pode levar à insuficiência renal. Utilizando algoritmos de aprendizado de máquina, este projeto busca classificar pacientes com base em variáveis clínicas e laboratoriais, contribuindo para diagnósticos mais ágeis e eficientes.

O projeto foi desenvolvido com a linguagem **Python** utilizando a plataforma **Google Colaboratory**.

## 📁 Arquivos do Repositório

- `DoençaCronicaRenal.ipynb`: Notebook principal contendo o código da pesquisa. Ele inclui todas as etapas de pré-processamento, treinamento, avaliação dos modelos e conclusões.
- `RelatorioDaPesquisa.pdf`: Documento final da pesquisa, com embasamento teórico, justificativas, metodologia utilizada, descrição dos algoritmos, análise dos resultados e referências. Recomendado para quem deseja se aprofundar na pesquisa ou entender detalhes do dataset.
- `kidney_disease_train.csv`: Arquivo com os dados de treinamento utilizados pelos modelos de aprendizado.
- `kidney_disease_test.csv`: Arquivo com os dados de teste utilizados para validar a performance dos modelos.

## ⚙️ Tecnologias Utilizadas

- Python (pandas, scikit-learn, matplotlib, seaborn, etc.)
- Google Colaboratory
- Algoritmos de ML: KNN, Random Forest, SVM, Regressão Logística, entre outros

## 📊 Dataset

O conjunto de dados utilizado é baseado em registros médicos anonimizados com atributos como:
- Nível de creatinina
- Hemoglobina
- Pressão arterial
- Gravidade da urina
- Presença de proteína, açúcar, entre outros

O dataset foi dividido entre arquivos de treinamento e teste, disponíveis neste repositório.

## 🚀 Como Executar

1. Acesse o notebook `DoençaCronicaRenal.ipynb` via [Google Colab](https://colab.research.google.com/).
2. Faça upload dos arquivos `kidney_disease_train.csv` e `kidney_disease_test.csv` no ambiente Colab.
3. Execute as células do notebook passo a passo.

## 📚 Referência

Caso tenha dúvidas sobre o funcionamento do código, dos algoritmos utilizados ou do conjunto de dados, consulte o `RelatorioDaPesquisa.pdf`.
