## **Algebra**

-   **Slope-Intercept Form of a Line:** $y = mx + b$

-   **Quadratic Formula:** $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

-   **Factoring Example:** $ax^2 + bx + c = a(x - r_1)(x - r_2)$

------------------------------------------------------------------------

### **Trigonometry**

-   **Basic Sine Function:** \`$y = \sin(x)$

-   **Amplitude and Phase Shift:**

$y = A \sin(B(x - C)) + D$

Amplitude: $|A|$

Period: $\frac{2\pi}{B}$

Phase Shift: $C$

Vertical Shift: $D$

-   **Sine Shift Example:**

$y = \sin(x - \frac{\pi}{2})$ shifts right by $\frac{\pi}{2}$

-   **Pythagorean Identity:** $\sin^2(x) + \cos^2(x) = 1$

------------------------------------------------------------------------

### **Pre-Calculus / Exponential & Logarithmic Functions**

**Exponential Growth/Decay:** $A = A_0 e^{rt}$

**Natural Logarithm:** $y = \ln(x)$

------------------------------------------------------------------------

### Linear Algebra

### **Vectors**

-   **Vector Notation:** `markdown $\vec{v} = \begin{bmatrix} v_1 \ v_2 \ \vdots \ v_n \end{bmatrix}$`

-   **Dot Product:** `markdown $\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2 + \cdots + a_n b_n$`

-   **Length (Norm) of a Vector:** `markdown $|\vec{v}| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$`

------------------------------------------------------------------------

### **Matrices**

-   **Matrix Notation:** `markdown $A = \begin{bmatrix} a_{11} & a_{12} \ a_{21} & a_{22} \end{bmatrix}$`

-   **Matrix Multiplication:** `markdown $(AB)_{ij} = \sum_{k=1}^n a_{ik}b_{kj}$`

-   **Identity Matrix:** `markdown $I_n = \begin{bmatrix} 1 & 0 & \cdots & 0 \ 0 & 1 & \cdots & 0 \ \vdots & \vdots & \ddots & \vdots \ 0 & 0 & \cdots & 1 \end{bmatrix}$`

------------------------------------------------------------------------

### **Systems of Equations**

-   **Matrix Form:** `markdown $A\vec{x} = \vec{b}$`

-   **Solution (if \$A\$ is invertible):** `markdown $\vec{x} = A^{-1} \vec{b}$`

------------------------------------------------------------------------

### **Determinant**

-   **2×2 Matrix Determinant:** `markdown $\det \begin{bmatrix} a & b \ c & d \end{bmatrix} = ad - bc$`

------------------------------------------------------------------------

### **Eigenvalues and Eigenvectors**

-   **Eigenvalue Equation:** $A \vec{v} = \lambda \vec{v}$

-   **Characteristic Equation:** $\det(A - \lambda I) = 0$

------------------------------------------------------------------------

#### **Transpose and Inverse**

-   **Transpose:** $(A^T)_{ij} = A_{ji}$

-   **Inverse (for 2×2 matrix):** $A^{-1} = \frac{1}{ad-bc} \begin{bmatrix} d & -b \ -c & a \end{bmatrix}$

#### Singular Value Decomposition (SVD)
For any real $m \times n ) matrix ( A )$:

$A = U \Sigma V^T$
( U ): an ( m \times m ) orthogonal (or unitary) matrix.
( \Sigma ): an ( m \times n ) diagonal matrix with non-negative real numbers (the singular values) on the diagonal.
( V^T ): the transpose of an ( n \times n ) orthogonal (or unitary) matrix ( V ).
Expanded Form Example:

$A = U \Sigma V^T = 
\begin{bmatrix}
  | &  & | \\
  \vec{u}_1 & \cdots & \vec{u}_m \\
  | &  & |
\end{bmatrix}
\begin{bmatrix}
  \sigma_1 & 0 & \cdots & 0 \\
  0 & \sigma_2 & \cdots & 0 \\
  \vdots & \vdots & \ddots & \vdots \\
  0 & 0 & \cdots & \sigma_n \\
\end{bmatrix}
\begin{bmatrix}
  - & \vec{v}_1^T & - \\
  & \vdots & \\
  - & \vec{v}_n^T & -
\end{bmatrix}
$

### **Calculus**

-   **Derivative Definition:** $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$

-   **Power Rule:** $\frac{d}{dx} x^n = n x^{n - 1}$

-   **Integral (Indefinite):** $\int x^n , dx = \frac{x^{n+1}}{n+1} + C$

------------------------------------------------------------------------

### **Differential Equations**

-   **First-Order Linear ODE:** $\frac{dy}{dt} + P(t) y = Q(t)$

-   **General Solution to Homogeneous Second-Order ODE:** $y'' + a y' + b y = 0$

Solution: $y(t) = C*1 e^{r*1 t} + C*2 e^{r*2 t}$ where $r*1, r*2$ solve $r^2 + a r + b = 0$

-   **Exponential Solution Example:** $A = A_0 e^{rt}$
