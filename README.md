Descrição do trabalho (evolução das implementações) a estrela

Este projeto implementa o algoritmo A* e evolui a aplicação de forma incremental. Primeiro, o A* foi validado em um grafo pequeno e fixo para confirmar a lógica do caminho mínimo. Em seguida, o grafo passou a ser gerado automaticamente como uma matriz N×N, sendo o n escolhido pelo usuario -com  movimentos  apenas norte, sul, leste, oeste e como opcional é possivel adicional movimentos diagonais- e o resultado começou a ser exibido no terminal como um “mapa” em formato de grade.


Depois, o projeto foi expandido para uma simulação em turnos, onde um caçador recalcula o A* a cada passo. O comportamento de alvo móvel (pega-pega) foi adicionado como opção: o alvo pode ficar fixo ou se mover aleatoriamente a cada turno. Para aumentar a complexidade sem alterar a lógica do A*, foram adicionados obstáculos no tabuleiro, melhorias de visualização (legenda e símbolos) e variações configuráveis de dificuldade: obstáculos móveis (opcional) e aumento de obstáculos por turno (opcional), permitindo ao usuário escolher o nível de desafio, além disso o usuário é capaz de escolher a duração máxima de turnos da partida.
