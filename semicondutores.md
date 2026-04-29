É estudado por conta que diferente do ideal os semicondutores tem linearidades que afetam o sistema.

o que mais vamos avaliar nessa disciplina é o IGBT, MOSFET e BJT por que eles trabalham em alta frequencia

O primeiro que estudamos é o diodo de potencia
- tensão unipolar -> só alimentado de um forma
- corrente unidirecional -> só conduz em um sentido

diodos em conversores chaveados são usados como diodo de roda livre (dar um caminho para a corrente do indutor/ descarregar o indutor)

queda de condução do diodo é uma função da dopagem (mas no slide esta como aproximadamente 1V)

diferente do diodo ideal um real conduz corrente negativa durante um tempo especifico -> caracteristica indesejavel

prefrencialmente não usar em paralelo devido ao seu coeficiente negativo de temperatura q leva a distribuiçcão de corrente desigual

3 tipos de dido de silicio
- diodo de uso padrão
    - operaçcão em baixo frequencia
    - normalmente fabricantes n especificão o trr
    - possuem baixa uqeda de condução
- diodo de recuperação rapida
    - utilizado em fontes chaveadas
    - fabricantes especificam trr e Qr
- diodo schottky
    - tempo de recuperação desprezivel
    - menor queda de tensão comparado com diodos convencionais
    - maior corrente reversa em regime permanente
    - dificilmente encontrado para tensões maiores de 100V
