# VectorVelocityComponentAux

This object computes a component of a vector-valued velocity field.

The vector velocity is computed as:
\begin{equation}
\vec{u} = \frac{rhouA}{rhoA} \vec{d}
\end{equation}
$\vec{u}$ is velocity vector, $\vec{d}$ is the direction of the element, $rhoA$ is density multiplied by cross-sectional area, and $rhouA$ is momentum density multiplied by cross-sectional area.

!alert note
$\rho u A$ and $\rho A$ are variables usually defined by the [Components](syntax/Components/index.md).

!syntax parameters /AuxKernels/VectorVelocityComponentAux

!syntax inputs /AuxKernels/VectorVelocityComponentAux

!syntax children /AuxKernels/VectorVelocityComponentAux
