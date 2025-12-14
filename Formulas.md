# Math Formulas

## Algebra
- **Slope-intercept form:** $y = mx + b$
- **Point-slope form:** $y - y_1 = m(x - x_1)$
- **Standard form of a line:** $Ax + By = C$ with slope $m = -\tfrac{A}{B}$
- **Quadratic formula:** $x = \dfrac{-b \pm \sqrt{b^{2} - 4ac}}{2a}$
- **Vertex of $ax^2 + bx + c$:** $\left(-\dfrac{b}{2a}, -\dfrac{D}{4a}\right)$ where $D = b^2 - 4ac$
- **Factored form of a quadratic:** $ax^2 + bx + c = a(x - r_1)(x - r_2)$ with roots $r_1, r_2$
- **Distance between points $(x_1, y_1)$ and $(x_2, y_2)$:** $d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$
- **Midpoint between points $(x_1, y_1)$ and $(x_2, y_2)$:** $\left(\dfrac{x_1 + x_2}{2},\, \dfrac{y_1 + y_2}{2}\right)$

## Trigonometry
- **Basic definitions:** $\sin(x)$, $\cos(x)$, $\tan(x) = \dfrac{\sin(x)}{\cos(x)}$
- **Graph parameters for $y = A\sin(B(x - C)) + D$ (or $\cos$):**
  - Amplitude: $|A|$
  - Period: $\dfrac{2\pi}{|B|}$
  - Phase shift: $C$
  - Vertical shift: $D$
- **Pythagorean identity:** $\sin^{2}(x) + \cos^{2}(x) = 1$
- **Angle addition identities:**
  - $\sin(\alpha \pm \beta) = \sin \alpha \cos \beta \pm \cos \alpha \sin \beta$
  - $\cos(\alpha \pm \beta) = \cos \alpha \cos \beta \mp \sin \alpha \sin \beta$
- **Law of sines:** $\dfrac{\sin A}{a} = \dfrac{\sin B}{b} = \dfrac{\sin C}{c}$
- **Law of cosines:** $c^{2} = a^{2} + b^{2} - 2ab\cos C$ (cyclic for other sides)

## Exponential & Logarithmic Functions
- **Exponential growth/decay:** $A(t) = A_0 e^{kt}$ with rate $k$
- **Compound interest:** $A(t) = P \left(1 + \dfrac{r}{n}\right)^{nt}$ and continuous compounding $A(t) = Pe^{rt}$
- **Natural logarithm:** $y = \ln x$ with derivative $\dfrac{d}{dx}\ln x = \dfrac{1}{x}$
- **Logarithm properties:**
  - $\log_b(MN) = \log_b M + \log_b N$
  - $\log_b\left(\dfrac{M}{N}\right) = \log_b M - \log_b N$
  - $\log_b(M^{k}) = k\,\log_b M$
  - **Change of base:** $\log_b M = \dfrac{\ln M}{\ln b}$

## Linear Algebra
### Vectors
- **Vector notation:** $\vec{v} = \begin{bmatrix} v_1 \\ v_2 \\ \vdots \\ v_n \end{bmatrix}$
- **Magnitude (norm):** $\lVert\vec{v}\rVert = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$
- **Dot product:** $\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2 + \cdots + a_n b_n$
- **3D cross product:** $\vec{a} \times \vec{b} = (a_2 b_3 - a_3 b_2,\ a_3 b_1 - a_1 b_3,\ a_1 b_2 - a_2 b_1)$
- **Projection of $\vec{a}$ onto $\vec{b}$:** $\mathrm{proj}_{\vec{b}}\,\vec{a} = \frac{\vec{a}\cdot\vec{b}}{\lVert\vec{b}\rVert^{2}}\,\vec{b}$

### Matrices

- **Identity matrix:** $I_n$ has $1$ on the diagonal and $0$ elsewhere.
- **Transpose:** $(A^T)_{ij} = A_{ji}$
- **Matrix multiplication:** $(AB)_{ij} = \sum_{k=1}^{n} a_{ik} b_{kj}$
- **2×2 determinant:**  
  If $A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$, then $\det(A) = ad - bc$
- **3×3 determinant (rule of Sarrus):**  
  If $A$ is  
  $[a\ b\ c]$  
  $[d\ e\ f]$  
  $[g\ h\ i]$,  
  then $\det(A) = aei + bfg + cdh - ceg - bdi - afh$
- **2×2 inverse (when $ad - bc \neq 0$):**  
  If $A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$, then  
  $A^{-1} = (1/(ad - bc)) \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}$

### Systems of Linear Equations
- **Matrix form:** $A\vec{x} = \vec{b}$
- **Solution (if $A$ is invertible):** $\vec{x} = A^{-1}\vec{b}$

### Eigenvalues and Eigenvectors
- **Eigenvalue equation:** $A\vec{v} = \lambda \vec{v}$
- **Characteristic equation:** $\det(A - \lambda I) = 0$

### Singular Value Decomposition (SVD)
For any real $m \times n$ matrix $A$:
- $A = U \Sigma V^{T}$
- $U$: $m \times m$ orthogonal (or unitary) matrix
- $\Sigma$: $m \times n$ diagonal matrix with non-negative singular values
- $V^{T}$: transpose of an $n \times n$ orthogonal (or unitary) matrix $V$

## Calculus
- **Limit definition of derivative:** $f'(x) = \lim_{h \to 0} \dfrac{f(x + h) - f(x)}{h}$
- **Power rule:** $\dfrac{d}{dx} x^{n} = n x^{n-1}$
- **Product rule:** $\dfrac{d}{dx}(fg) = f' g + f g'$
- **Chain rule:** $\dfrac{d}{dx} f(g(x)) = f'(g(x)) \cdot g'(x)$
- **Common derivatives:** $\dfrac{d}{dx} e^{x} = e^{x}$, $\dfrac{d}{dx} \ln x = \dfrac{1}{x}$
- **Indefinite integral:** $\int x^{n}\,dx = \dfrac{x^{n+1}}{n+1} + C \quad (n \neq -1)$
- **Definite integral (Fundamental Theorem):** $\displaystyle \int_{a}^{b} f'(x)\,dx = f(b) - f(a)$
- **Integration by parts:** $\displaystyle \int u\,dv = uv - \int v\,du$

## Differential Equations
- **First-order linear ODE:** $\dfrac{dy}{dt} + P(t) y = Q(t)$ with integrating factor $\mu(t) = e^{\int P(t)\,dt}$ and solution $y = \dfrac{1}{\mu(t)}\left(\int \mu(t) Q(t)\,dt + C\right)$
- **Homogeneous second-order ODE:** $y'' + a y' + b y = 0$ with solution $y(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}$ where $r_{1,2}$ solve $r^{2} + a r + b = 0$
- **Exponential growth/decay model:** $A(t) = A_0 e^{kt}$
