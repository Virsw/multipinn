# 11. 2D NS lid-driven flow (NS2d-C).

The PDE is given by

$$\mathbf{u} \cdot \nabla\mathbf{u} + \nabla p - \frac{1}{Re}\Delta\mathbf{u} = \mathbf{0}, \quad \mathbf{x} \in \Omega$$

$$\nabla \cdot \mathbf{u} = 0, \quad \mathbf{x} \in \Omega$$

The domain is $\Omega = [0,1]^2$, the top boundary is $\Gamma_1$, the left, right and bottom boundary is $\Gamma_2$.

The boundary conditions are

$$\mathbf{u}(\mathbf{x}) = (ax(1-x), 0), \quad \mathbf{x} \in \Gamma_1$$

$$\mathbf{u}(\mathbf{x}) = (0,0), \quad \mathbf{x} \in \Gamma_2$$

$$p = 0, \quad \mathbf{x} = (0,0).$$

The Reynolds number $Re = 100$, $a=4$.

Data: [lid_driven_a4.dat](https://disk.yandex.ru/d/8cYMQthwn7fv-Q) should be placed at `examples/navier_stokes_2D_C/data/lid_driven_a4.dat`.

This file needs to be downloaded if you want to calculate the error between the PINN's and numeric solutions.
