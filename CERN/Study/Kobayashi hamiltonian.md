#Study

Kobayashi hamiltonian work in discrete time. It represents the trajectories of particles in phase space where one point is a position of a particle.

![[Pasted image 20231222090841.png]]

Consider the case of $Q \approx 1/3$ (fractional part). This tune is close to the third resonance. In this case it takes 3 turns for a particle to make a full turn in phase space.  

Trajectories close to the reference point are closed and have triangular-like shapes. Particles with $Q > 1/3$ have infinite trajectories. Case  $Q = 1/3$ corresponds to separatrix (resonance). 

Hamiltonian for $Q \approx 1/3$ has the following form:  
$$H_3 = \frac{\mu}{2} (x^2 + p^2) + \frac{g}{12} (x^3 - 3xp^2)$$
where $\mu = 2\pi \delta Q$, $g = \beta_x^{3/2} g_{ph}$.
For a given energy $H$ equation $H_3(x) = H$ has maximum 3 roots. Trajectory $H(x, p) = H_s$ corresponds to separatrix, in this case $H_3(x) = H$ has less then 3 roots. In order to find $H_s$, let us define the function $F(x) = H(x) - H$. $F(x) = 0$ has 2 roots when $F(x)$ looks like this:
![[Pasted image 20231222093552.png]].
In other words, $F(x_{extr}) = 0$, where $x_{exstr}$ is so that $F'(x_{exstr}) = 0$. 

$$F'(x) = \mu x + \frac{g}{4} (x^2 - p^2)$$
Then
$$x_{extr} = -\frac{2\mu}{g} \pm \sqrt{\frac{4\mu^2}{g^2} - p^2}$$

For simplicity let us consider $p = 0$. This does change the outcome, because $H_s (x, p) = \text{const}$. Case $x_{extr} = 0$ is trivial ($H = 0$). The second root is $$x_{extr} = - \frac{4\mu}{g}$$
Corresponding $$F(x_{extr}) = \frac{(2\mu)^3}{3g^2} - H_s = 0$$, thus
$$H_s = \frac{(2\mu)^3}{3g^2}$$
 Given that, we represent $H_3 = H_s + P_3(x)$, where $P_3(x)$  is 3rd order polynomial having 3 real roots $x_1$, $x_2$ and $x_3$. In other words, $P_3(x)$ can be factorised. Let us find $P_3(x)$ roots. $$P_3(x) = \frac{\mu}{2} (x^2 + p^2) + \frac{g}{12} (x^3 - 3xp^2) - \frac{(2\mu)^3}{3g^2}$$
 The first one can be found by putting the sum of the terms with $p^2$ equal to 0. 
 $$\frac{\mu}{2}p^2 - \frac{g}{12} \cdot 3x_1 p^2 = 0$$
 $$x_1 = \frac{2\mu}{g}$$
In fact this number is not necessarily a root in general case, we are just lucky enough to guess it right.
Knowing this it is possible to separate the factor $x - x_1$ from expression for $P_3$, find $x_2$ and $x_3$ and factorise the expression.
$$P_3(x) = \frac{g}{12} \left(x-\frac{2\mu}{g}\right) \left(x - \sqrt 3 p + \frac{4\mu}{g}\right) \left(x + \sqrt 3 p + \frac{4\mu}{g}\right)$$
That gives you the hamiltonian
$$H_3(x, p) = \frac{(2\mu)^3}{3g^2} + \frac{g}{12} \left(x-\frac{2\mu}{g}\right) \left(x - \sqrt 3 p + \frac{4\mu}{g}\right) \left(x + \sqrt 3 p + \frac{4\mu}{g}\right)$$
Equations 
$$x = x_1 = \frac{2\mu}{g}$$
$$x = x_2(p) =>p = \frac{1}{\sqrt 3} (x + \frac{4\mu}{g}) $$
$$x = x_3(p) =>p = -\frac{1}{\sqrt 3} (x + \frac{4\mu}{g}) $$
