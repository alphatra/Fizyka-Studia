#### Poziom
- średni
#### Źródło
- [Test Elektryczność i Magnetyzm - Test Semestralny](https://forms.office.com/Pages/ResponseDetailPage.aspx?id=-b5xKxM7MkS19B9awieNDHc_TpPNOUxDgodrutpdKORUQ0tXMjJMTkNHVVMzR1NFVkJNTUlTRkNNVSQlQCN0PWcu&rid=22&GetResponseToken=XvVGiy20FFVTV7pjGbzHgi2Bo3R-0IPHOZvaaL_iQ4Y)
## Treść
---
Pole magnetyczne opisane poniższą zależnością działa na płaską pętlę o polu powierzchni A i oporze R. Jeśli kąt α pomiędzy wektorem powierzchni i osią x jest stały, jaka zostanie wyindukowana SEM i jakie będzie natężenie prądu w obwodzie? ⁣
$B=B_{x}=0.2\cos \omega t [T]$
## Odpowiedzi
---
- [ ] $E=\frac{0.2}{A}\omega \sin \omega t\cos \alpha, I=\frac{0.2R\omega}{A}\sin \omega t \cos \alpha$
- [x] $E=0.2A\omega \sin \omega t\cos \alpha, I=\frac{0.2A\omega}{A}\sin \omega t \cos \alpha$
- [ ] $E=0.2A\cos \omega t\cos \alpha, I= \frac{0.2A}{R}\cos \omega t \cos \alpha$
- [ ] $E=-0.2A\omega \sin \omega t\cos \alpha, I=-\frac{0.2A\omega}{A}\sin \omega t \cos \alpha$
## Obliczenia
---
$$
\begin{flalign*}
\text{Dane:} &&\\
&\text{Pole powierzchni S = A},\\
&\text{Opór R = const},\\
&\text{Kąt pomiędzy wektorem powierzchni}\\
&\text{a wektorem natężenia pola elektrycznego}, \\
&\alpha=\text{const},\\
&B=B_{x}=0.2\cos \omega t [T], \\
\text{Szukane:} &&\\
&\text{SEM=?}, \\
&\text{I=?}, \\
\text{Wzory:} &&\\
&SEM=-\frac{d\Phi_{B}}{dt},\\
&\Phi=BS\cos \alpha\\
&R=\frac{U}{I}, \\
\text{Obliczenia:}&&
\end{flalign*}
$$
$$
\begin{align}
R&=\frac{U}{I} \\
&=\frac{SEM}{I} \\ 
\implies I&=\frac{SEM}{R} \\ \\
\Phi_{B}&=0.2\cos (\omega t)\cdot A\cos \alpha \\
\frac{d\Phi_{B}}{dt}&=\omega\cdot (-0.2\sin(\omega t))\cdot A\cos \alpha \\
SEM &= 0.2⋅ω⋅A⋅cos(α)⋅sin(ωt) \\
I&=\frac{0.2Aω}{R}cos(α)⋅sin(ωt)
\end{align}
$$
$$
\begin{gather}

\end{gather}
$$
```tikz \usepackage{circuitikz} \begin{document} \begin{circuitikz}[american, voltage shift=0.5] \draw (0,0) to[isource, l=$I_0$, v=$V_0$] (0,3) to[short, -*, i=$I_0$] (2,3) to[R=$R_1$, i>_=$i_1$] (2,0) -- (0,0); \draw (2,3) -- (4,3) to[R=$R_2$, i>_=$i_2$] (4,0) to[short, -*] (2,0); \end{circuitikz} \end{document} ```
## Linki
---
[[Pole magnetyczne]]
[[Rezystancja - Prawo Ohma ( Ω )]]