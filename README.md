# Redes Temporais de Co-Autoria

## Autores: 
### • Lucas Garcia Costa   

### • Maurício Matheus Araújo Silva Galvão  

Neste projeto foram analisadas cuidadosamente redes temporais de co-autoria nos seguintes formatos:

• Anuais (2010-2025);   

• Trienais; 

• Quadrienais;   

• Geral.     



### Na Base de dados com redes temporais de co-autoria anuais foram estudados:  



• Número de vértices;

• Número de arestas;   

• Número médio de vizinhos;  

• Densidade da rede;    

• Distribuição do número médio de vizinhos.    

  
  
Para uma visualização precisa utilizamos bibliotecas do Python como Matplotlib e Joyplot para plotagem, fazendo inicialmente um gráfico único contendo detalhadamente 4 das métricas mencionadas, além de utilizar uma IA generativa como o ChatGPT-4.1 para explorar novos métodos dessas bibliotecas com o intuito de aplicar melhorias aos gráficos já feitos.  

### Exemplo de prompt utilizado: 

![image](https://github.com/user-attachments/assets/73c6d02b-c769-40ce-90f0-62741915f1c1)  

### Gráfico de 4 curvas:



![image](https://github.com/user-attachments/assets/8236914e-7333-49bb-9d29-6ce5df85f9f8)


Em seguida, foi feito um histograma inicial para visualização da distribuição do número de vizinhos.


![image](https://github.com/user-attachments/assets/d0884a91-100c-45b6-aeae-616406cb9bc6)


Após esse histograma fizemos um Ridgeline Chart contendo detalhadamente, de forma mais visível o comportamento da distribuição do número de vizinhos, ou distribuição de grau de cada rede de co-autoria (2010-2025).


![image](https://github.com/user-attachments/assets/29162a5a-f8df-4a8b-9b43-81001d361fa9)


Tendo essa parte finalizada, analisamos agora as redes de citação dos períodos de avaliação do PPgEEC, tendo o tamanho do vértice proporcional ao número de vizinhoscom destaque aos top 5 vértices
com mais vizinhos em cor distinta. A cor da aresta sendo vermelha em caso de uma ligação entre membros permanentes do PPgEEC e preta caso contrário, enquanto a largura é proporcional à quantidade de citações.


* Por as imagens e análises(as analises são basicamente identicas, mudando só a facilidade de vizualização pelo quão populoso é o grafo)


Em um ambito mais geral, temos a vizualização dos grafos da rede de citações geral(2010 a 2024) e do sub-grafo em que só mantemos os vertices que tenham pelo menos 71 vizinhos.


* Colocar a imagem dos grafos lado a lado


Suas densidades são de aproximadamente 0.87% e 27.22%, respectivamente, esse crescimento é explicado por nessa filtragem, ao diminuir o número de vertices, diminui-se o numero máximo de arestas numa taxa quadratica, enquanto mantemos aqueles com mais conexões, fazendo com que o número presente de arestas diminua devagar, assim aumentando a proporção entre esses valores, ou seja, a densidade.


E por fim, vemos um grafo ego de um vertice aleatoriamente escolhido dentre o grafo geral


* Imagem do grafo ego
