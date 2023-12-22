#Study

Kobayashi hamiltonian work in discrete time. It represents the trajectories of particles in phase space where one point is a position of a particle.

![[Pasted image 20231222090841.png]]

Consider the case of $Q \approx 1/3$ (fractional part). This tune is close to the third resonance. In this case it takes 3 turns for a particle to make a full turn in phase space.  

Trajectories close to the reference point are closed and have triangular-like shapes. Particles with $Q > 1/3$ have infinite trajectories. Case  $Q = 1/3$ corresponds to separatrix (resonance). 

Hamiltonian for $Q \approx 1/3$ has the following form:  
$$H_3 = \frac{\mu}{2} (x^2 + p^2) + \frac{g}{12} (x^3 - 3xp^2)$$
For a given energy $H$ equation $H_3(x) = H$ has maximum 3 roots. Trajectory $H(x, p) = H_s$ corresponds to separatrix, in this case $H_3(x) = H$ has less then 3 roots. In order to find $H_s$, let us define the function $F(x) = H(x) - H$. $F(x) = 0$ has 2 roots when $F(x)$ looks like this:
![[Pasted image 20231222093552.png]].
In other words, $F(x_{extr}) = 0$, where $x_{exstr}$ is so that $F'(x_{exstr}) = 0$. 

$$F'(x) = \mu x + \frac{g}{4} (x^2 - p^2)$$
Then
$$x_{extr} = -\frac{2\mu}{g} \pm \sqrt{\frac{4\mu^2}{g^2} - p^2}$$

For simplicity let us consider $p = 0$. This does change the outcome, because $H_s (x, p) = \text{const}$. Case $x_{extr} = 0$ is trivial ($H = 0$). The second root is $$x_{extr} = - \frac{4\mu}{g}$$
Corresponding $$F(x_{extr}) = \frac{(2\mu)^3}{3g^2} - H_s = 0$$, thus
$$H_s = \frac{(2\mu)^3}{3g^2}$$
 Given that, we represent $H_3 = H_s + P_3(x)$, where $P_3(x)$  is 3rd order polynomial having 3 real roots. In other words, $P_3(x)$ can be factorised. Let us find $P_3(x)$ roots. $$P_3(x) = \frac{\mu}{2} (x^2 + p^2) + \frac{g}{12} (x^3 - 3xp^2) - \frac{(2\mu)^3}{3g^2}$$