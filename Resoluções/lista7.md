# Resolução lista 7

1. Resposta: As trajetórias são concorrentes. Entretanto, não há colisão
	
	Considere $A = (0,0,0)$ um ponto de $r$, $\vec{u} = (1,2,4)$ um vetor diretor de $r$, $B = (1, 0, -2)$ um ponto de $s$ e $\vec{v} = (1, 1, 1)$ um vetor diretor de $s$.
	
	$r$ é concorrente a $s$ $\Leftrightarrow \vec{u}, \vec{v}\:LI$ e $\vec{AB}, \vec{u}, \vec{v}$ LD.

	Como $(1,2,4)$, não é paralelo a $(1, 1, 1)$, a primeira condição está satisfeita.

	Como $\begin{vmatrix} 1 & 2 & 4 \\\ 1 & 1 & 1 \\\ 1 & 0 & -2 \end{vmatrix} = 0$, a segunda condição é satisfeita e, portanto, as trajetórias são concorrentes.

	Para determinar se há colisão, deve-se encontrar um ponto que satisfaça o as duas equações com o mesmo coeficiente linear $\lambda$.

	Tem-se que $r: \begin{cases} x = \lambda \\\ y = 2\lambda \\\ z = 4\lambda \end{cases}$ e $s: \begin{cases} x = 1 + \lambda \\\ y = \lambda \\\ z = -2 + \lambda \end{cases}, \lambda \in \mathbb{R}$. Portanto, o ponto de colisão teria que satisfazer o sistema $\begin{cases} \lambda = 1 + \lambda \\\ 2\lambda = \lambda \\\ 4\lambda = -2 + \lambda \end{cases}$, que é impossível. Portanto, não há colisão.

2. $A = (2, 0, -3)$
	1. Resposta: $r: \begin{cases} x = 2 + \lambda \\\ y = \lambda \\\ z = -3 -\lambda\end{cases}$
	
		A reta que passa pelos pontos $B$ e $C$ tem como vetor diretor $\vec{BC} = (1, 1, -1)$.
		 
	2. Resposta: $r: \begin{cases} x = 2 - 5\lambda \\\ y = \frac{4}{3}\lambda \\\ z =  6\lambda\end{cases}$
		
		$s:\frac{1-x}{5} = \frac{3y}{4} = \frac{z+3}{6}$

		Seguindo a definição da equação simétrica da reta: $s:\begin{cases} \frac{1-x}{5} = \lambda \\\ \frac{3y}{4} = \lambda \\\ \frac{z+3}{6} = \lambda\end{cases} \Rightarrow s:\begin{cases} x = 1 - 5\lambda \\\ y = \frac{4}{3}\lambda \\\ z = -3 + 6\lambda\end{cases}$

		Portanto, um vetor diretor de $s$ é $(-5, \frac{4}{3}, 6)$

	3. Resposta: $r: \begin{cases} x = 2 - 2\lambda \\\ y = \lambda \\\ z =  -\lambda\end{cases}$

		Já que um vetor diretor de $s$ é $(2, 1, -1)$.

3. :
	1. Resposta:
		$\pi_1: x + y + z + 1 = 0$
		$\pi_2: x - y - z = 0$
		$\pi_3: x + 2y - z - 2 = 0$
		
		Um vetor normal a $\pi_1$ é $\vec{AB} \wedge \vec{AC} = (-1,1,0)\wedge(-1,0,1) = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\\ -1 & 1 & 0 \\\ -1 & 0 & 1 \end{vmatrix} = \hat{i} + \hat{j} + \hat{k}$. Portanto, $\pi_1: x + y + z + d = 0$. Substituindo $x$, $y$ e $z$ pelas coordenadas de $A$ (ponto do plano) tem-se $1 + 0 + 0 + d = 0 \therefore d = -1$

		Um vetor normal a $\pi_2$ é $\vec{u} \wedge \vec{v} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\\ 0 & 1 & -1 \\\ 1 & 0 & 1 \end{vmatrix} = \hat{i} - \hat{j} - \hat{k}$> portanto, $\pi_2: x - y - z + d = 0$. Substituindo $x$, $y$ e $z$ pelas coordenadas de $Q$ (ponto do plano) tem-se $-1 - (-1) + 0 + d = 0 \therefore d = 0$

		Um vetor normal a $\pi_3$ é $(-2,1,0)\wedge(1,0,1) = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\\ -2 & 1 & 0 \\\ 1 & 0 & 1 \end{vmatrix} = \hat{i} + 2\hat{j} - \hat{k}$. Portanto, $\pi_3: x + 2y - z + d = 0$. Substituindo $x$, $y$ e $z$ pelas coordenadas $(1,1,1)$ (ponto do plano) tem-se $1 + 2 - 1 + d = 0 \therefore d = -2$
		
	2. No sistema $\begin{cases} x + y + z + 1 = 0 \\\ x - y - z = 0 \\\ x + 2y - z - 2 = 0\end{cases}$
	
		Somando a primeira equação com a segunda tem-se $2x + 1 = 0 \therefore x = -\frac{1}{2}$.
	
		Na primeira com a terceira tem-se $2x + 3y -1 = 0 \Rightarrow 2(-\frac{1}{2}) + 3y -1 = 0 \therefore y = \frac{2}{3}$

		Então, na primeira equação $-\frac{1}{2} + \frac{2}{3} + z + 1 = 0 \therefore z = -\frac{7}{6}$

		Uma vez que os valores encontrados para as três incognitas satisfazem as três equações, é correto afirmar que o sistema é possível e determinado. Portanto, tem apenas um ponto como intersecção entre os três planos.
4. Para a resolução de todos os itens é recomendável encontrar a equação vetorial de todas as retas.
	
	$r:\begin{cases} x = my - 1 \\\ z = y - 1 \end{cases} \Rightarrow r:\begin{cases} x = -1 + m\lambda \\\ y = \lambda \\\ z = -1 + \lambda\end{cases}, \lambda \in \mathbb{R} \Rightarrow r:  X=\overbrace{(-1,0,-1)}^A + \lambda \overbrace{(m, 1, 1)}^{\vec{u}}, \lambda \in \mathbb{R}$

	$s: x= \frac{y}{m} = z \Rightarrow s: \begin{cases} x=\lambda \\\ y = m\lambda \\\ z=\lambda \end{cases}, \lambda \in \mathbb{R} \Rightarrow s: X=\overbrace{(0,0,0)}^B + \lambda \overbrace{(1, m, 1)}^{\vec{v}}, \lambda \in \mathbb{R}$

	$t: -x+z = y = -z-1 \Rightarrow t:\begin{cases} -x + z = y \\\ -z -1 = y \end{cases}$ somando as duas equações tem-se $t: \begin{cases} -x - 1 = 2y \\\ -z -1 = y \end{cases} \Rightarrow t:\begin{cases} -x - 1 = 2\lambda \\\ y = \lambda \\\ -z -1 = \lambda \end{cases} \Rightarrow t: \begin{cases} x = -1 -2\lambda \\\ y = \lambda \\\ z= -1 -\lambda \end{cases} \Rightarrow t: X=\overbrace{(-1,0,-1)}^C + \lambda \overbrace{(-2, 1, -1)}^{\vec{w}}, \lambda \in \mathbb{R}$

   1. Resposta: $m = 1$

	 	$r \parallel s \iff \vec{u} \parallel \vec{v} \iff (m,1,1) = k(1,m,1) \Rightarrow k = 1, m = 1$

		 Como $B$ não satisfaz a equação de $r$, as retas não são coincidentes e o valor de $m$ é válido.
	2. Resposta: $m = 0$ ou $m = 1$.
		
		$r$, $s$ e $t$ paralelas a um mesmo plano $\iff \vec{u},\vec{v},\vec{w}$ LD $\iff \begin{vmatrix} m & 1 & 1 \\\ 1 & m & 1 \\\ -1 & 0 & -1 \end{vmatrix} = 0 \Rightarrow -m^2 + m= 0 \Rightarrow m_1 = 0, m_2 = 1$