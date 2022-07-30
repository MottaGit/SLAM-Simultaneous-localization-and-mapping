# SLAM-Simultaneous-localization-and-mapping
Algoritmo de simulação de SLAM usando python desenvolvido para treinar habilidades de programação e ampliar a compreenssão sobre robética e veículos autônomos no geral.

A implementação do SLAM consiste em três etapas:
__mapping__
1 - Medição de pontos com sensor LIDAR: usa lasers para medir distâncias dos objetos.
2 - Algoritmo para encontrar retas: elaborar um algoritmo que estime retas a partir dos pontos lidos pelos sensores, essas retas serão os obstáculos/paredes/objetos que estarão ao redor do robô. artigo que descreve esse algoritmo em: <https://journals.sagepub.com/doi/pdf/10.1177/1729881418755245>
__localization__
3 - Localizar a posição atual a partir de pontos de referência: como escolher bons pontos de ref a partir dos recursos de linhas gerados anteriormente?

O algoritmo desenvolvido aqui implementa apenas a etapa da simulação do sensor LIDAR. Ele lê uma imagem de uma planta baixa de uma casa, e a setinha do mouse simula o sensor, conforme o usuário avança o mouse na tela ele mapeia os pontos, armazena em um vetor e imprime na tela.

![image](https://user-images.githubusercontent.com/66978224/181866138-fb4701d8-b0ce-4236-b45c-2249e02b7824.png)
imagem da planta real usada como entrada do sistema.

![image](https://user-images.githubusercontent.com/66978224/181866112-050931df-b6b2-40af-a903-c5184d4bdf0b.png)
imagem da planta mapeada pelo sensor LIDAR.
