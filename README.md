# kafka_xgboost_nsga3
Otimização Apache Kafka com XGBoost Surrogate e NSGA-III - Artigo e Projeto de Dissertação

Este é um conjunto de procedimentos para otimização de Produtores do Apache Kafka. 

Visa um ambiente laboratorial de estudos acadêmicos, mas pode servir para treinamento e estudos em ambiente profissional.

Este experimento foi criado para fins de dissertação de mestrado (PEL/UERJ).

A otimização é realizada por meio da integração de aprendizado de máquinas (XGBoost) + Algoritmo Evolutivo Multiobjetivo (NSGA-III).

Os scripts estão escritos em shell e python. 

O roteiro para o ambiente é
  1) Criar máquinas virtuais (testado com Ubuntu Server 24);
  2) Destinar uma máquina para produtor, outra para o cluster (recomendado 3);
  3) Recomendo criar uma máquina para servir de consumidor e uma máquina para monitoramento de métricas (opcionais);
  4) Instalar o Apache Kafka. Na máquina produtora, basta uma instalação standalone. Nas máquinas do cluster, configurar para que todas as máquinas estejam realmente em cluster (1, 2, 3, 4, ...). Configure o java se precisar (no experimento foi adotado o padrão de fábrica)
  5) Seguir o roteiro de testes. Para instalações, sugiro seguir a IA de sua preferência para apoio dessas atividades inciais;

Roteiro de Testes e Scripts


Arquivos de Testes Realizados (Uso Liberado)


Artigos Relacionados



