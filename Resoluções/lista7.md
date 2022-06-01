# Resolução lista 7

1. As trajetórias são concorrentes. Entretanto, não há colisão
	
	Considere $A = (0,0,0)$ um ponto de $r$, $\vec{u} = (1,2,4)$ um vetor diretor de $r$, $B = (1, 0, -2)$ um ponto de $s$ e $\vec{v} = (1, 1, 1)$ um vetor diretor de $s$.
	
	$r$ é concorrente a $s$ $\Leftrightarrow \vec{u}, \vec{v}\:LI$ e $\vec{AB}, \vec{u}, \vec{v}$ LD.

	Como $(1,2,4)$, não é paralelo a $(1, 1, 1)$, a primeira condição está satisfeita.

	Como $\begin{vmatrix} 1 & 2 & 4 \\\ 1 & 1 & 1 \\\ 1 & 0 & -2 \end{vmatrix} = 0$, a segunda condição é satisfeita e, portanto, as trajetórias são concorrentes.

	Para determinar se há colisão, deve-se encontrar um ponto que satisfaça o as duas equações com o mesmo coeficiente linear $\lambda$.

	Tem-se que $r: \begin{cases} x = \lambda \\\ y = 2\lambda \\\ z = 4\lambda \end{cases}$ e $s: \begin{cases} x = 1 + \lambda \\\ y = \lambda \\\ z = -2 + \lambda \end{cases}, \lambda \in \mathbb{R}$. Portanto, o ponto de colisão teria que satisfazer o sistema $\begin{cases} \lambda = 1 + \lambda \\\ 2\lambda = \lambda \\\ 4\lambda = -2 + \lambda \end{cases}$, que é impossível. Portanto, não há colisão.

2. $A = (2, 0, -3)$
   1. $\begin{cases} x = 2 + \lambda \\\ y = \lambda \\\ z = -3 -\lambda\end{cases}$
	 
	 	A reta que passa pelos pontos $B$ e $C$ tem como vetor diretor $\vec{BC} = (1, 1, -1)$.
		 
	2. $\begin{cases} x = 2 - 5\lambda \\\ y = \frac{4}{3}\lambda \\\ z =  6\lambda\end{cases}$
		
		$s:\frac{1-x}{5} = \frac{3y}{4} = \frac{z+3}{6}$

		Seguindo a definição da equação simétrica da reta: $s:\begin{cases} \frac{1-x}{5} = \lambda \\\ \frac{3y}{4} = \lambda \\\ \frac{z+3}{6} = \lambda\end{cases} \Rightarrow s:\begin{cases} x = 1 - 5\lambda \\\ y = \frac{4}{3}\lambda \\\ z = -3 + 6\lambda\end{cases}$

		Portanto, um vetor diretor de $s$ é $(-5, \frac{4}{3}, 6)$ 