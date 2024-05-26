Нека $f:\mathbb{R}^n \implies \mathbb{R}^m$. Тогава $`f(x_1, \dots,x_n)=\begin{bmatrix} f_1(x_1,\dots,x_n) \\ \vdots \\ f_m(x_1,\ldots, x_m) \end{bmatrix}`$, тъй като третираме всяка координата в резултата като отделна функция. $f$ да е диференцируема в $x_0 \in \mathbb{R}^n$ означава съществуването на линеен оператор $df(x_0):\mathbb{R}^n \implies \mathbb{R}^m$ такъв, че $f(x_0+h)=f(x_0)+df(x_0)(h)+o(||h||)$. Тогава $f_1, \dots, f_m$ са диференцируеми в $x_0$ и

```math

df(x_0)(h)=\begin{bmatrix}
  \frac{\partial f_1}{\partial x_1} & 
    \ldots & 
    \frac{\partial f_1}{\partial x_n} \\[1ex]
  \vdots & \ddots & \vdots \\[1ex]
  \frac{\partial f_m}{\partial x_1} & 
    \ldots & 
    \frac{\partial f_m}{\partial x_n}
\end{bmatrix}
\begin{bmatrix} h_1 \\ \vdots \\ h_n \end{bmatrix} =
\begin{bmatrix}
  grad f_1(x_0) \\[1ex]
  \vdots \\[1ex]
  grad f_m(x_0)
\end{bmatrix}
\begin{bmatrix} h_1 \\ \vdots \\ h_n \end{bmatrix}
```

Отново правим апроксимация, просто за всяка координата поотделно (умножение на матрици).
