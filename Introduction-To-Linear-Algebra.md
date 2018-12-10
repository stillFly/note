# Introduction To Linear Algebra

by Gilbert Strang

[TOC]

## 1. Introduction to Vectors

### 1.1 Vectors and Linear Combinations

_Def:_

> Vector Addition
>
> ​	$v = \begin{bmatrix}v_1\\v_2\end{bmatrix}$ and $w = \begin{bmatrix}w_1 \\ w_2\end{bmatrix}$ add to $v + w = \begin{bmatrix}v_1 + w_1\\v_2 + w_2\end{bmatrix}$.
>
> Scalar Multiplication
>
> ​	$2v = \begin{bmatrix}2v_1 \\ 2v_2\end{bmatrix}$ and $-v = \begin{bmatrix}-v_1 \\ -v_2\end{bmatrix}$.
>
> Linear Combinations
>
> ​	The sum of $cv$ and $dw$ is a *linear combination* of $v$ and $w$.

The Important Questions

> What is the picture of all combinations $cu$, $cu + dv$ and $cu + dv + ew$?($u, v, w \neq 0$)
>
> 1. The combinations $cu$ fill a **line**.
> 2. The combinations $cu + dv$ fill a **plane**.
> 3. The combinations $cu + dv + ew$ fill **three-dimensional space**.(The line $ew$ is not in the plane of $u$ and $v$.)

### 1.2 Lengths and Dot Products

_Def:_

> **Dot product** or **Inner product**($v=(v_1, v_2)$ and $w=(w_1,w_2)$)
>
> ​	$v \cdot w = v_1w_1 + v_2w_2$
>
> **length**(or **norm**) of a vector $v$
>
> ​	 $length = \lVert v \rVert = \sqrt{v \cdot v}$
>
>