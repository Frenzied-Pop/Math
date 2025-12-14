# Mathematical Symbols Reference

Concise lookup for commonly used mathematical notation. Symbols are grouped by topic and include brief notes or examples for context.

## Number Sets and Constants

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\mathbb{N}$ | Natural numbers | Often $\{1,2,3,\dots\}$; some texts include $0$ |
| $\mathbb{Z}$ | Integers | $\{\dots,-2,-1,0,1,2,\dots\}$ |
| $\mathbb{Q}$ | Rational numbers | Fractions $p/q$ with integers $p,q \neq 0$ |
| $\mathbb{R}$ | Real numbers | Includes rationals and irrationals |
| $\mathbb{C}$ | Complex numbers | $a + bi$ with real $a,b$ |
| $\mathbb{R}^{n}$ | $n$-dimensional real space | Column vectors of length $n$ |
| $\emptyset$ | Empty set | Contains no elements |
| $\infty$ | Infinity | Used in limits and intervals |
| $i$ or $\mathrm{j}$ | Imaginary unit | $i^2 = -1$ |
| $\pi$ | Pi | Circle constant $\approx 3.14159$ |
| $e$ | Euler's number | Base of natural logarithm $\approx 2.71828$ |

## Arithmetic and Algebra

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $+$, $-$, $\times$, $\div$ | Basic operations | Addition, subtraction, multiplication, division |
| $\pm$ | Plus or minus | Quadratic roots, tolerances |
| $\cdot$ | Dot / scalar multiplication | Avoids ambiguity in algebraic products |
| $\ast$ | Convolution or generic product | Common in signals and algebra |
| $/$ | Fraction bar | Division or ratio |
| $=$ | Equality | States two expressions are identical |
| $\approx$ | Approximately equal | Numerical approximations |
| $\equiv$ | Identically equal / congruent | Algebraic identities or modular equality |
| $\neq$ | Not equal | Inequality |
| $<$, $\leq$, $>$, $\geq$ | Order relations | Less/greater than (or equal to) |
| $\propto$ | Proportional to | $y \propto x$ means $y = kx$ |
| $\sqrt{\,}$ | Square root | $\sqrt[n]{\,}$ for $n$th roots |
| $|x|$ | Absolute value | Distance from zero |
| $x^{n}$ | Power | Exponentiation |
| $\log$, $\ln$ | Logarithms | $\log$ base indicated by context; $\ln$ base $e$ |

## Set Theory and Logic

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\in$ | Element of | $x \in A$ |
| $\notin$ | Not an element of | $x \notin A$ |
| $\subset$, $\subseteq$ | Proper / non-strict subset | Dual symbols $\supset$, $\supseteq$ |
| $\cup$ | Union | $A \cup B$ |
| $\cap$ | Intersection | $A \cap B$ |
| $\setminus$ | Set difference | Elements in $A$ not in $B$ |
| $A^{c}$ | Complement | Elements not in $A$ |
| $\forall$ | For all | Universal quantifier |
| $\exists$ | There exists | Existential quantifier |
| $\nexists$ | There does not exist | Negated existential |
| $\implies$ | Implies | Logical implication |
| $\iff$ | If and only if | Biconditional |
| $\neg$ | Not | Logical negation |
| $\wedge$ | And | Logical conjunction |
| $\vee$ | Or | Logical disjunction |

## Geometry and Trigonometry

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\angle ABC$ | Angle at $B$ | Rays $BA$ and $BC$ |
| $\triangle ABC$ | Triangle with vertices $A,B,C$ | Similar notation $\square ABCD$ for quadrilateral |
| $\parallel$ | Parallel lines | $\ell_1 \parallel \ell_2$ |
| $\perp$ | Perpendicular lines | $\ell_1 \perp \ell_2$ |
| $\circ$ | Degree measure | $90^\circ$ |
| $\text{rad}$ | Radians | $\pi$ rad $= 180^\circ$ |
| $\pi r^2$ | Circle area | With circumference $2\pi r$ |
| $\sin$, $\cos$, $\tan$, $\csc$, $\sec$, $\cot$ | Trigonometric functions | Reciprocal identities |
| $\arcsin$, $\arccos$, $\arctan$ | Inverse trig functions | Principal values |
| $\Delta$ | Difference or triangle | Context-dependent |

## Calculus

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\dfrac{d}{dx}$ | Derivative operator | Rate of change with respect to $x$ |
| $\partial$ | Partial derivative | $\dfrac{\partial f}{\partial x}$ |
| $\nabla$ | Gradient / del operator | $\nabla f$, $\nabla \cdot \vec{F}$, $\nabla \times \vec{F}$ |
| $\int$, $\iint$, $\iiint$ | Integral signs | Single, double, triple integrals |
| $\oint$ | Line or contour integral | Closed path integral |
| $\sum$, $\prod$ | Summation and product | Limits indicated below/above symbols |
| $\lim$ | Limit | $\lim_{x \to a} f(x)$ |
| $\frac{dy}{dt}$ | Total derivative | Time derivative; dot notation $\dot{y}$ also common |
| $\bigcup$, $\bigcap$ | Indexed union/intersection | Often used with limits on sets |

## Linear Algebra and Vectors

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\vec{v}$ or $\mathbf{v}$ | Vector | Boldface or arrow notation |
| $\|\vec{v}\|$ | Norm / length | Euclidean norm unless specified |
| $\cdot$ | Dot product | $\vec{u} \cdot \vec{v}$ |
| $\times$ | Cross product | $\vec{u} \times \vec{v}$ in $\mathbb{R}^3$ |
| $A^{T}$ | Transpose | Swap rows and columns |
| $A^{-1}$ | Inverse matrix | Exists when $\det A \neq 0$ |
| $\det(A)$ | Determinant | Area/volume scaling factor |
| $\operatorname{rank}(A)$ | Rank | Dimension of column space |
| $\lambda$ | Eigenvalue | In $A\vec{v} = \lambda \vec{v}$ |
| $\Sigma$ | Singular values (SVD) | Diagonal matrix in SVD |

## Probability and Statistics

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $P(A)$ | Probability of event $A$ | $0 \le P(A) \le 1$ |
| $P(A \mid B)$ | Conditional probability | Read “probability of $A$ given $B$” |
| $A \perp B$ | Independence | Events or variables independent |
| $E[X]$ | Expected value | Mean of random variable $X$ |
| $\operatorname{Var}(X)$ | Variance | $E[(X - E[X])^2]$ |
| $\sigma$ | Standard deviation | $\sqrt{\operatorname{Var}(X)}$ |
| $\mu$ | Population mean | Parameter of a distribution |
| $\binom{n}{k}$ | Binomial coefficient | $\dfrac{n!}{k!(n-k)!}$ |
| $f_X(x)$ | Probability density / mass function | Depends on whether $X$ is continuous or discrete |
| $\Phi(z)$ | Normal CDF | Standard normal cumulative distribution |

## Logic, Algorithms, and Miscellaneous

| Symbol | Meaning | Notes |
| --- | --- | --- |
| $\lceil x \rceil$ | Ceiling | Smallest integer $\ge x$ |
| $\lfloor x \rfloor$ | Floor | Greatest integer $\le x$ |
| $\mod$ | Modulus / remainder | $a \bmod n$ |
| $\uparrow$, $\downarrow$ | Increasing / decreasing | Monotonic trends |
| $\because$, $\therefore$ | Because / therefore | Proof punctuation |
| $\Rightarrow$ | Yields / then | Often used in derivations |
| $\mapsto$ | Maps to | $x \mapsto f(x)$ |
| $\forall$ ... $\exists$ | Quantifier pair | Used in definitions and proofs |
| $\Box$ | End of proof | “Q.E.D.” symbol |
| $\otimes$, $\oplus$ | Tensor / direct sum | Linear algebra and group theory |
| $\hbar$ | Reduced Planck constant | Physics contexts |

## Greek Alphabet (common mathematical uses)

| Symbol | Name | Typical Uses |
| --- | --- | --- |
| $\alpha$ | alpha | Angles, coefficients |
| $\beta$ | beta | Angles, coefficients |
| $\gamma$ | gamma | Angles, Euler–Mascheroni constant $\gamma$ |
| $\delta$ | delta | Difference, small increment, Kronecker delta $\delta_{ij}$ |
| $\Delta$ | Delta | Discriminant, change, Laplacian $\nabla^2$ |
| $\epsilon$ | epsilon | Arbitrarily small positive number |
| $\varepsilon$ | epsilon (variant) | Alternate small quantity |
| $\zeta$ | zeta | Riemann zeta $\zeta(s)$ |
| $\eta$ | eta | Efficiency, viscosity |
| $\theta$ | theta | Angles, parameters |
| $\vartheta$ | theta (variant) | Special trig/elliptic contexts |
| $\iota$ | iota | Index, inclusion map |
| $\kappa$ | kappa | Curvature, condition number |
| $\lambda$ | lambda | Eigenvalues, wavelengths |
| $\mu$ | mu | Mean, micro- prefix |
| $\nu$ | nu | Frequency, neutrinos |
| $\xi$ | xi | Random variables, Riemann xi |
| $o$, $\omicron$ | omicron | Rarely used symbol |
| $\pi$ | pi | Circle constant, product symbol $\Pi$ |
| $\varpi$ | pi (variant) | Specialized contexts |
| $\rho$ | rho | Density, correlation |
| $\sigma$ | sigma | Summations $\Sigma$, standard deviation |
| $\tau$ | tau | Time constant, torsion |
| $\upsilon$ | upsilon | Rarely used |
| $\phi$ | phi | Golden ratio, angles |
| $\varphi$ | phi (variant) | Alternate notation |
| $\chi$ | chi | Characteristic function, Euler characteristic |
| $\psi$ | psi | Wavefunctions, digamma $\psi$ |
| $\omega$ | omega | Angular frequency; $\Omega$ for ohms or big-Omega |

