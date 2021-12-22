## KDD Cup 1999 Data (https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

Conjunto de dados usado para a Terceira Competição Internacional de Ferramentas de Mineração de Dados e Descoberta de Conhecimento, que foi realizada em conjunto com a KDD-99, a Quinta Conferência Internacional sobre Descoberta de Conhecimento e Mineração de Dados.

- Adaptado do artigo "Cost-based Modeling and Evaluation for Data Mining With Application to Fraud and Intrusion Detection: Results from the JAM Project", de Salvatore J. Stolfo, Wei Fan, Wenke Lee, Andreas Prodromidis e Philip K. Chan.

- Uma conexão é uma sequência de pacotes TCP começando e terminando em alguns momentos bem definidos, entre os quais os dados fluem de e para um endereço IP de origem para um endereço IP de destino sob algum protocolo bem definido. Cada conexão é rotulada como normal ou como um ataque, com exatamente um tipo de ataque específico. Cada registro de conexão consiste em cerca de 100 bytes.


O dataset foi preparado pelo MIT Lincoln Labs através de intrusões simuladas em um ambiente de rede militar, em 1998, e possui as seguintes características: colunas = 42 Linhas = 4.898.429

Os ataques se enquadram em quatro categorias principais:

- DOS: negação de serviço, por exemplo inundação de syn (syn flood);
- R2L: acesso não autorizado de uma máquina remota, por ex. adivinhando a senha;
- U2R: acesso não autorizado a privilégios de superusuário (root) local, por exemplo, vários ataques de "buffer overflow";
- Sondagem (Probing): vigilância e outra sondagem, por exemplo, varredura de porta.

O código está sendo desenvolvido em Python com as bibliotecas Pandas, Numpy, Matplotlib, Sklearn e outras.

## Update:

O projeto passou a usar o dataset NSL-KDD que é, segundo [1], uma versão do dataset original do KDD Cup 1999 que visa corrigir alguns problemas inerentes mencionados pelos autores. Embora não seja uma representação perfeita das redes reais existentes, devido a falta de datasets públicos para NIDS, os autores acreditam que pode ser aplicado como referência para ajudar pesquisadores.

O dataset utilizado neste projeto foi o KDDTrain+.txt.

Tanto os datasets como maiores informações sobre o NLS-KDD, estão no site do Canadian Institute for Cybersecurity: https://www.unb.ca/cic/datasets/nsl.html

[1] - M. Tavallaee, E. Bagheri, W. Lu, and A. Ghorbani, “A Detailed Analysis of the KDD CUP 99 Data Set,” Submitted to Second IEEE Symposium on Computational Intelligence for Security and Defense Applications (CISDA), 2009.

## Modelos de classificação binária e multiclasse utilizados no projeto:

- Gradient Boosting Classifier (GBC)
- Linear Support Vector Machine Classifier (LSVM)
- K-Nearest Neighbors Classifier (KNN)
- Gaussian Naive Bayes Classifier (GNB)
- Logistic Regression Classifier (LR)
- Random Forest Classifier (RF)
