
1. Define:

	(a) Subgraph
R: Trata-se de uma pequena fração do gráfico total
	
	(b) Bipartite graph.
R: Definido quando os vértices de um gráfico podem ser divididos em dois conjuntos dijuntos
	
	(c) Hamiltonian graph
R: É caracterizado quando o gfrafo possui o ciclo fechado que por sua vez visita cada vértice apenas uma vez
	
	(d) Eulerian graph.
R: Em seu conceito é tido que um grafo euleriano é todo aquele que é impossível cobrir todos os vértices sem retraçar nenhuma aresta. Desse modo, fazendo um passeio fechado pelo grafo que visita cada aresta exatamente uma vez e retorna ao vértice inicial.

2. Describe how a breadth-first search algorithm works.

R: Funciona de modo em que ele começa na raiz da árvore ou gráfico e investiga todos os nós no nível de profundidade atual antes de passar para os nós no próximo nível de profundidade 

3. How many edges does a complete graph with n vertices have? What about a complete directed graph with n vertices?

R: Um gráfico completo possui uma aresta entre dois vértices quaisquer. Você pode obter uma vantagem escolhendo dois vértices quaisquer. Portanto, se houver n vértices, haverá n escolha

4. What are isomorphic graphs? Draw an example.
   
R: Os gráficos são isomórficos se houver uma estrutura que preserve uma correspondência um-para-um entre os vértices e as arestas.

![Isomórfico graph](https://github.com/terrematte/network_analysis/assets/40202382/20e2a373-f9b4-47e2-9657-6922647504e0)



5. Calculate the degree of the nodes for both node types in the bipartite adjacency matrix from the figure below. Find the isolated node(s).

![adjacency matrix](./img/matrix01.png)

6. Given the digraph `G = (V, E)` where `V = {M, N, O, P, Q, R, S}` and 

`E ={(M, S), (N, O), (P, R), (N, S), (O, M),
	 (N, Q), (O, M), (P, P), (S, M), (O, N), 
	 (S, M), (N, R), (P, M), (M, S)}`

	(a) Specify, if any, a simple path from vertex M to vertex S.

	(b) Specify, if any, a simple cycle, involving at least 4 nodes.

	(c) Is the digraph connected or not connected?

	(d) What is the degree of vertices N and R.

	(e) Represent the digraph using adjacency list representation.

	(f) Represent the digraph using adjacency matrix representation.

7. Draw the undirected and directed versions of the graph G(V, E), where V = {1, 2, 3, 4, 5, 6} and E = {(2, 5), (6, 1), (5, 3), (2, 3)}.

8. How many edges does a graph have 3 vertices of degree 3 and one vertex of degree 5?

9. Mr. A is friend with Mrs. B, but she doesn't like him back. She has a reciprocal friendship with both C and D, but only C considers D a friend. D has also sent friend requests to E, F, G, and H but, so far, only G replied. G also has a reciprocal relationship with A. Draw the corresponding directed graph.

10. Draw the graph from the previous exercise as undirected and weighted, with the weight being 2 if the connection is reciprocal, 1 otherwise.

