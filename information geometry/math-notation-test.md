# Some math notation


## LaTeX

<img src="https://i.upmath.me/svg/%7C%5Cvec%7BA%7D%7C%3D%5Csqrt%7BA_x%5E2%20%2B%20A_y%5E2%20%2B%20A_z%5E2%7D." alt="|\vec{A}|=\sqrt{A_x^2 + A_y^2 + A_z^2}." />(1)

integrals:

<img src="https://i.upmath.me/svg/P_%5Comega%3D%7Bn_%5Comega%5Cover%202%7D%5Chbar%5Comega%5C%2C%7B1%2BR%5Cover%201-v%5E2%7D%5Cint%5Climits_%7B-1%7D%5E%7B1%7Ddx%5C%2C(x-v)%7Cx-v%7C%2C" alt="P_\omega={n_\omega\over 2}\hbar\omega\,{1+R\over 1-v^2}\int\limits_{-1}^{1}dx\,(x-v)|x-v|," />

cool tikz-pictures:

<img src="https://i.upmath.me/svg/%5Cusetikzlibrary%7Bdecorations.pathmorphing%7D%0A%5Cbegin%7Btikzpicture%7D%5Bline%20width%3D0.2mm%2Cscale%3D1.0545%5D%5Csmall%0A%5Ctikzset%7B%3E%3Dstealth%7D%0A%5Ctikzset%7Bsnake%20it%2F.style%3D%7B-%3E%2Csemithick%2C%0Adecoration%3D%7Bsnake%2Camplitude%3D.3mm%2Csegment%20length%3D2.5mm%2Cpost%20length%3D0.9mm%7D%2Cdecorate%7D%7D%0A%5Cdef%5Ch%7B3%7D%0A%5Cdef%5Cd%7B0.2%7D%0A%5Cdef%5Cww%7B1.4%7D%0A%5Cdef%5Cw%7B1%2B%5Cww%7D%0A%5Cdef%5Cp%7B1.5%7D%0A%5Cdef%5Cr%7B0.7%7D%0A%5Ccoordinate%5Blabel%3Dbelow%3A%24A_1%24%5D%20(A1)%20at%20(%5Cww%2C%5Cp)%3B%0A%5Ccoordinate%5Blabel%3Dabove%3A%24B_1%24%5D%20(B1)%20at%20(%5Cww%2C%5Cp%2B%5Ch)%3B%0A%5Ccoordinate%5Blabel%3Dbelow%3A%24A_2%24%5D%20(A2)%20at%20(%5Cw%2C%5Cp)%3B%0A%5Ccoordinate%5Blabel%3Dabove%3A%24B_2%24%5D%20(B2)%20at%20(%5Cw%2C%5Cp%2B%5Ch)%3B%0A%5Ccoordinate%5Blabel%3Dleft%3A%24C%24%5D%20(C1)%20at%20(0%2C0)%3B%0A%5Ccoordinate%5Blabel%3Dleft%3A%24D%24%5D%20(D)%20at%20(0%2C%5Ch)%3B%0A%5Cdraw%5Bfill%3Dblue!14%5D(A2)--(B2)--%20%2B%2B(%5Cd%2C0)--%20%2B%2B(0%2C-%5Ch)--cycle%3B%0A%5Cdraw%5Bgray%2Cthin%5D(C1)--%20%2B(%5Cw%2B%5Cd%2C0)%3B%0A%5Cdraw%5Bdashed%2Cgray%2Cfill%3Dblue!5%5D(A1)--%20(B1)--%20%2B%2B(%5Cd%2C0)--%20%2B%2B(0%2C-%5Ch)--%20cycle%3B%0A%5Cdraw%5Bdashed%2Cline%20width%3D0.14mm%5D(A1)--(C1)--(D)--(B1)%3B%0A%5Cdraw%5Bsnake%20it%5D(C1)--(A2)%20node%5Bpos%3D0.6%2Cbelow%5D%20%7B%24c%5CDelta%20t%24%7D%3B%0A%5Cdraw%5B-%3E%2Csemithick%5D(%5Cww%2C%5Cp%2B0.44*%5Ch)--%20%2B(%5Cw-%5Cww%2C0)%20node%5Bpos%3D0.6%2Cabove%5D%20%7B%24v%5CDelta%20t%24%7D%3B%0A%5Cdraw%5Bsnake%20it%5D(D)--(B2)%3B%0A%5Cdraw%5Bthin%5D(%5Cr%2C0)%20arc%20(0%3Aatan2(%5Cp%2C%5Cw)%3A%5Cr)%20node%5Bmidway%2Cright%2Cyshift%3D0.06cm%5D%20%7B%24%5Ctheta%24%7D%3B%0A%5Cdraw%5Bopacity%3D0%5D(-0.40%2C-0.14)--%20%2B%2B(0%2C5.06)%3B%0A%5Cend%7Btikzpicture%7D" alt="\usetikzlibrary{decorations.pathmorphing}
\begin{tikzpicture}[line width=0.2mm,scale=1.0545]\small
\tikzset{&gt;=stealth}
\tikzset{snake it/.style={-&gt;,semithick,
decoration={snake,amplitude=.3mm,segment length=2.5mm,post length=0.9mm},decorate}}
\def\h{3}
\def\d{0.2}
\def\ww{1.4}
\def\w{1+\ww}
\def\p{1.5}
\def\r{0.7}
\coordinate[label=below:$A_1$] (A1) at (\ww,\p);
\coordinate[label=above:$B_1$] (B1) at (\ww,\p+\h);
\coordinate[label=below:$A_2$] (A2) at (\w,\p);
\coordinate[label=above:$B_2$] (B2) at (\w,\p+\h);
\coordinate[label=left:$C$] (C1) at (0,0);
\coordinate[label=left:$D$] (D) at (0,\h);
\draw[fill=blue!14](A2)--(B2)-- ++(\d,0)-- ++(0,-\h)--cycle;
\draw[gray,thin](C1)-- +(\w+\d,0);
\draw[dashed,gray,fill=blue!5](A1)-- (B1)-- ++(\d,0)-- ++(0,-\h)-- cycle;
\draw[dashed,line width=0.14mm](A1)--(C1)--(D)--(B1);
\draw[snake it](C1)--(A2) node[pos=0.6,below] {$c\Delta t$};
\draw[-&gt;,semithick](\ww,\p+0.44*\h)-- +(\w-\ww,0) node[pos=0.6,above] {$v\Delta t$};
\draw[snake it](D)--(B2);
\draw[thin](\r,0) arc (0:atan2(\p,\w):\r) node[midway,right,yshift=0.06cm] {$\theta$};
\draw[opacity=0](-0.40,-0.14)-- ++(0,5.06);
\end{tikzpicture}" />

plots:

<img src="https://i.upmath.me/svg/%5Cbegin%7Btikzpicture%7D%5Bscale%3D1.0544%5D%5Csmall%0A%5Cbegin%7Baxis%7D%5Baxis%20line%20style%3Dgray%2C%0A%09samples%3D120%2C%0A%09width%3D9.0cm%2Cheight%3D6.4cm%2C%0A%09xmin%3D-1.5%2C%20xmax%3D1.5%2C%0A%09ymin%3D0%2C%20ymax%3D1.8%2C%0A%09restrict%20y%20to%20domain%3D-0.2%3A2%2C%0A%09ytick%3D%7B1%7D%2C%0A%09xtick%3D%7B-1%2C1%7D%2C%0A%09axis%20equal%2C%0A%09axis%20x%20line%3Dcenter%2C%0A%09axis%20y%20line%3Dcenter%2C%0A%09xlabel%3D%24x%24%2Cylabel%3D%24y%24%5D%0A%5Caddplot%5Bred%2Cdomain%3D-2%3A1%2Csemithick%5D%7Bexp(x)%7D%3B%0A%5Caddplot%5Bblack%5D%7Bx%2B1%7D%3B%0A%5Caddplot%5B%5D%20coordinates%20%7B(1%2C1.5)%7D%20node%7B%24y%3Dx%2B1%24%7D%3B%0A%5Caddplot%5Bred%5D%20coordinates%20%7B(-1%2C0.6)%7D%20node%7B%24y%3De%5Ex%24%7D%3B%0A%5Cpath%20(axis%20cs%3A0%2C0)%20node%20%5Banchor%3Dnorth%20west%2Cyshift%3D-0.07cm%5D%20%7B0%7D%3B%0A%5Cend%7Baxis%7D%0A%5Cend%7Btikzpicture%7D" alt="\begin{tikzpicture}[scale=1.0544]\small
\begin{axis}[axis line style=gray,
	samples=120,
	width=9.0cm,height=6.4cm,
	xmin=-1.5, xmax=1.5,
	ymin=0, ymax=1.8,
	restrict y to domain=-0.2:2,
	ytick={1},
	xtick={-1,1},
	axis equal,
	axis x line=center,
	axis y line=center,
	xlabel=$x$,ylabel=$y$]
\addplot[red,domain=-2:1,semithick]{exp(x)};
\addplot[black]{x+1};
\addplot[] coordinates {(1,1.5)} node{$y=x+1$};
\addplot[red] coordinates {(-1,0.6)} node{$y=e^x$};
\path (axis cs:0,0) node [anchor=north west,yshift=-0.07cm] {0};
\end{axis}
\end{tikzpicture}" />
