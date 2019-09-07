# Projeto 3 - Ensinando um quadricóptero a voar
Terceiro projeto do NanoDegree de Engenheiro Machine Learning da Udacity. Consiste em aplicar técnicas de aprendizagem por reforço.

# Objetivo do Projeto
Possibilitar que quadricópteros assumam comportamentos de controle desejados, tais como decolagem e pouso, de forma autônoma. 

# Destaques do Projeto
Este projeto foi desenvolvido para se familiarizar com os muitos algoritmos de aprendizagem por reforço disponíveis.

Aprendizados com esse projeto:
- Deep Deterministic Policy Gradients (DDPG)
- Ruído Ornstein–Uhlenbeck

# Modelos Usados no Projeto
Foi usado uma rede neural com camadas diferentes. No final, foi combinado a ação com os estados e foi aplicado uma camada densa com ativação "relu", além da normalização em lote. Usei o agente DDPG.

# Resultados dos Modelos
Foi difícil treinar o agente. Tiver que pesquisar bastante e ver exemplos de outros códigos para chegar no meu resultado. Fora que a tarefa de treinamento demorou muito, por isso eu usei um número menor de episodios. Tive que instalar também o tensorflow e o keras. Tomei vários erros porque eu não tinha instalado ainda. Olhando para o gráfico de recompensas, o começo é bom, depois cai um pouco e fica meio irregular, até que depois o agente mantém um desempenho razoável e estável. A melhor recompensa ficou em 60.389.
