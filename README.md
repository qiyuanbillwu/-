## Gram-Schmidt Process

The Gram-Schmidt process is a method for orthonormalizing a set of vectors. Given a set of linearly independent vectors \( \mathbf{v}_1, \mathbf{v}_2, \ldots, \mathbf{v}_n \), the orthonormalized vectors \( \mathbf{u}_1, \mathbf{u}_2, \ldots, \mathbf{u}_n \) are computed as follows:

\[ \begin{align*}
\mathbf{u}_1 &= \mathbf{v}_1 \\
\mathbf{u}_2 &= \mathbf{v}_2 - \frac{\langle \mathbf{v}_2, \mathbf{u}_1 \rangle}{\lVert \mathbf{u}_1 \rVert^2} \mathbf{u}_1 \\
\mathbf{u}_3 &= \mathbf{v}_3 - \frac{\langle \mathbf{v}_3, \mathbf{u}_1 \rangle}{\lVert \mathbf{u}_1 \rVert^2} \mathbf{u}_1 - \frac{\langle \mathbf{v}_3, \mathbf{u}_2 \rangle}{\lVert \mathbf{u}_2 \rVert^2} \mathbf{u}_2 \\
&\vdots \\
\mathbf{u}_n &= \mathbf{v}_n - \sum_{i=1}^{n-1} \frac{\langle \mathbf{v}_n, \mathbf{u}_i \rangle}{\lVert \mathbf{u}_i \rVert^2} \mathbf{u}_i
\end{align*} \]

Where \( \langle \mathbf{v}, \mathbf{u} \rangle \) represents the inner product of vectors \( \mathbf{v} \) and \( \mathbf{u} \), and \( \lVert \mathbf{u} \rVert \) denotes the norm of vector \( \mathbf{u} \).
