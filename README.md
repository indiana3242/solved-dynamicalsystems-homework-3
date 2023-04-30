Download Link: https://assignmentchef.com/product/solved-dynamicalsystems-homework-3
<br>
Question 1 Compute a reduction to the central manifold up to 4th. order (i.e., including the 4th. order) for the system:

<table width="255">

 <tbody>

  <tr>

   <td width="22"><em>x</em>˙</td>

   <td width="25">=</td>

   <td width="207">−<em>y </em>+ <em>xz </em>− <em>x</em><sup>4</sup></td>

  </tr>

  <tr>

   <td width="22"><em>y</em>˙</td>

   <td width="25">=</td>

   <td width="207"><em>x </em>+ <em>yz </em>+ <em>xyz</em></td>

  </tr>

  <tr>

   <td width="22"><em>z</em>˙</td>

   <td width="25">=</td>

   <td width="207">−<em>z </em>− (<em>x</em><sup>2 </sup>+ <em>y</em><sup>2</sup>) + <em>z</em><sup>2 </sup>+ sin(<em>x</em><sup>3</sup>)<em>,</em></td>

  </tr>

 </tbody>

</table>

as well as the approximation to the dynamical equation on the manifold. Discuss which type of bifurcation is involved. Sketch the ow in the vicinity of the xed point at the origin. You may diagonalize the linear part (and work with complex variables), but it is simpler to just write the linearisation matrix in blocked form (one diagonal block for eigenvalues with zero real part, another diagonal block for the eigenvalue with negative real part) and work with real varibles throughout. Is the xed point stable? (Hint: Integrate numerically the equations on the manifold).

Question 2 Show that the system

<em>x</em><em>n</em>+1 =      <em>y</em><em>n</em>

<em>y</em><em>n</em>+1 =        <em>µ</em>1<em>y</em><em>n </em>+ <em>µ</em>2 − <em>x</em><em>n</em>2

can undergo saddle-node, period doubling and Hopf bifurcations when varying the parameters <em>µ</em><sub>1</sub>, <em>µ</em><sub>2</sub>. In other words, show curves in (<em>µ</em><sub>1</sub>, <em>µ</em><sub>2</sub>)-space along which the eigenvalues of the linearisation at the xed point(s) become non-hyperbolic in the three mentioned ways. Analyse the stability nearby in the simplest cases<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> (the analysis can be done numerically if you want, but it is better to give it a try with pencil, paper and a computer algebra programme). Side-hint: If an eigenvalue of a<sub>√ </sub>2×2 matrix is complex, then

it will look like√     <em>λ </em>= <em>A </em>±                    <em>B</em>, with <em>A,B </em>real and <em>B &lt; </em>0. In other words,

<em>λ </em>= <em>A </em>± <em>i </em>−<em>B </em>and |<em>λ</em>|<sup>2 </sup>= <em>A</em><sup>2 </sup>− <em>B</em>.

<a href="#_ftnref1" name="_ftn1">[1]</a> Some choices of (<em>µ</em><sub>1</sub><em>,µ</em><sub>2</sub>) lead to resonant (i.e., non-standard) Hopf bifurcations. Such values can be avoided in the excercise.