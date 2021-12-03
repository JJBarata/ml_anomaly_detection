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

O modelo de classificação que estou usando é o Gradient Boosting Classifier e o Linear Regression para comparar a precisão e outras métricas. Ainda está em andamento e meio desorganizado, mas conforme for evoluindo, irei organizar para ficar mais legível.

Caso queira ajudar, você será bem vindo.

Obrigado.
