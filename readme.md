# Algoritimo de Busca A* (Estrela)

O algoritmo de Busca A* (Estrela) é uma técnica de busca heurística utilizada para encontrar o caminho mais curto em um grafo, sendo amplamente aplicado em problemas de roteamento, como a navegação de GPS. Ele combina informações de custo e estimativas heurísticas para encontrar o caminho com o menor custo do ponto de partida até o ponto de destino.
##

<h2><strong>Ideia</strong></h2>
A ideia central do algoritmo é realizar uma busca por caminhos adjacentes, selecionando o caminho mais promissor com base na soma do custo acumulado do ponto de partida até o vértice atual e uma estimativa heurística da distância restante até o ponto de destino. Essa estimativa heurística é crucial para orientar o algoritmo na direção correta, evitando a exploração de caminhos menos promissores.

<h2>Implementação</h2>
Nesta implementação, o grafo é composto por vértices e arestas que representam as cidades e as distâncias entre elas. O algoritmo de Busca A* é aplicado para encontrar o caminho mais curto entre a cidade de Arad e Bucareste, utilizando a distância pela estrada entre as cidades como a heurística para orientar a busca.

<h2>Conclusão</h2>
O algoritmo de Busca A* é uma poderosa ferramenta para encontrar o caminho mais curto em um grafo, e suas aplicações vão além do cálculo de rotas em sistemas de navegação, sendo útil em diversas áreas, como inteligência artificial, jogos, robótica e planejamento de trajetos. Sua capacidade de combinar informações de custo com heurísticas eficientes o torna uma excelente escolha para resolver problemas de caminho mais curto em contextos reais.
