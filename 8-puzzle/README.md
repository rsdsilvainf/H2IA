
# H2IA - Jogo do 8-Puzzle

Este projeto implementa o clássico **Jogo do 8-Puzzle (Quebra-Cabeça de 8 Peças)** utilizando algoritmos de busca cega em Inteligência Artificial para encontrar a sequência de movimentos necessária para ordenar o tabuleiro.

## 🧠 Algoritmos Implementados

* **Busca em Largura (BFS - Breadth-First Search):** Explora o grafo de estados nível por nível. Garante encontrar a solução com o menor número de movimentos (ótima), mas consome mais memória operacional.
* **Busca em Profundidade (DFS - Depth-First Search):** Explora cada caminho até o limite máximo antes de realizar o retrocesso (*backtracking*). Pode encontrar soluções rapidamente, mas não garante o caminho mais curto.

## 🛠️ Como Executar

O projeto pode ser executado de duas formas:

### 1. Pelo Google Colab / Jupyter Notebook
Abra o arquivo `8-puzzle-bfs-dsf.ipynb` em seu ambiente de notebooks para visualizar o código segmentado, explicações detalhadas e os testes executados.

### 2. Pelo Terminal (Script Python)
Após realizar o download do repositório, você pode executar o script puro utilizando o Python no seu terminal. Certifique-se de passar o algoritmo desejado como argumento (exemplo):

```bash
python 8-puzzle-bfs-dsf.py
```

*Nota: Caso o seu script exija parâmetros de entrada para o estado inicial do tabuleiro, adicione-os logo após o nome do arquivo.*
