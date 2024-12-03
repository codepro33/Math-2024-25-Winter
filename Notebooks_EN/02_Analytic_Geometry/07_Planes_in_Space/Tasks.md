**Planes in Space**

**Task 1:**

Points:
- $A = (1, 2, 3)$
- $B = (3, 4, 5)$
- $C = (2, 1, 4)$

![alt text](image.png)

**Step 1: Calculate direction vectors**

It can be $\vec{AB}$ and $\vec{AC}$:
- $\vec{AB} = (B_x - A_x, B_y - A_y, B_z - A_z) = (3-1, 4-2, 5-3) = (2, 2, 2)$
- $\vec{AC} = (C_x - A_x, C_y - A_y, C_z - A_z) = (2-1, 1-2, 4-3) = (1, -1, 1)$

**Step 2: Finding normal vectors**

Normal vector can be found by taking cross product of $\vec{AB}$ and $\vec{AC}$:
$$
\vec{AB} \times \vec{AC} = 
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 2 & 2 \\
1 & -1 & 1 \\
\end{vmatrix} = \mathbf{i}(2 \cdot 1 - 2 \cdot (-1)) + \mathbf{j}(2 \cdot 1 - 2 \cdot 2) + \mathbf{k}(2 \cdot (-1) - 2 \cdot 1)
$$
$$
= \mathbf{i}(2 + 2) + \mathbf{j}(2 - 2) + \mathbf{k}(-2 - 2)
= 4\mathbf{i} - 0\mathbf{j} - 4\mathbf{k}
$$

The normal vector is: $(4, 0, -4)$.

We will use this to form the plane equation and substitute the point $A(1, 2, 3)$ to find $D$:

$$4x + 0y - 4z = D \rightarrow 4x - 4z = D$$

Substituting point $A(1, 2, 3)$:
$$4(1) - 4(3) = D$$
$$4 - 12 = D$$
$$D = -8$$

Thus, the equation of the plane is:
$$4x - 4z = -8$$

![alt text](image-1.png)
