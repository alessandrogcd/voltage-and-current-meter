# Open Hardware Device for Measure Voltage and Current in Didactic Laboratories

This device aims to reduce the number of equipment on a bench, reduce the possibility of spoiling them, and make a didactic experiment simpler and more practical.

Em experimentos que necessitam de medidas de parâmetros elétricos, como corrente, tensão e resistência, o multímetro é bastante utilizado, porém é necessário ajustá-los na escala e/ou função corretas, algumas situações exigem o uso de mais de um multímetro, um na escala de corrente e outro de tensão, por exemplo, o que neste caso pode complicar ainda mais a execução da tarefa, por ser necessário acompanhar as medidas dos dois equipamentos e anotar essas medidas.

Pensando nessas dificuldades deseja-se criar um equipamento: mais robusto, que não exija a mudança de escala, e nem mudança de função por possuir entrada tanto de corrente quanto de tensão; de baixo custo; que mostre as duas medidas ao mesmo tempo e com possibilidade de salvar essas medidas em um cartão de memória ou até mesmo enviá-las para o computador e compor um gráfico.

Para isso será utilizado um microcontrolador, um sensor de corrente e tensão, um display para mostrar os dados, um módulo de cartão de memória para armazenamento dos dados, um Mosfet com baixo Vgs para garantir leitura de tensão em somente um sentido e em relativamente baixas tensões, 3 botões para selecionar as funções do equipamento, 4 plugs para conectar fios de medida de tensão e corrente, um fusível para evitar correntes acima de determinado valor, uma placa que foi desenvolvida para fazer a conexão entre todos os equipamentos acima e ainda com a possibilidade de adicionar um dispositivo bluetooth.
