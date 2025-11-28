# Post Computer Modern

***Note:*** *So far nothing is here except an idea and a sketch of a “plan” for the following.*

Render an **OpenType** font family named $${\textbf{\color{blue}Post Computer Modern}}$$
that closely matches Donald E. Knuth’s font family $${\textbf{\color{blue}Computer Modern}}$$,
the font family used in the original LaTeX including by default in today’s pdflatex variant.

The idea is to generate this font family from the $${\textbf{\color{blue}METAFONT}}$$ font files,
probably using the programming language $${\textbf{\color{blue}Lua}}$$
and also publish the source for that.

Characters that were rendered from multiple glyphs,
like `ä` from `a` and `¨` or the ellipsis `…` from three `.`s,
would be mapped to corresponding Unicode characters.

Ideally a document that was written for the original LaTeX, including pdflatex,
with the default Computer Modern fonts
would very often render very close to identically
when rendered instead with $${\textbf{\color{blue}LuaLaTex}}$$ and using Post Computer Modern
with appropriate universal fontspec settings.

Since many in the LaTeX community seem to gravitate clearly towards LuaLaTeX
as the mainstream successor to pdflatex, as also announced in autumn 2024
by the TeX Users Group, it seems worthwhile to me to help provide the singular
beauty of the Computer Modern fonts also with LuaLaTeX with some additional comfort,
even though the fonts will not contain, say, Japanese glyphs.

Accordingly,
I hope to eventually release versions numbered $${\textbf{\color{green}1.6}}$$, $${\textbf{\color{green}1.61}}$$, $${\textbf{\color{green}1.618}}$$, …
(and maybe pre-releases $${\textbf{\color{red}0.6}}$$, $${\textbf{\color{red}0.61}}$$, $${\textbf{\color{red}0.618}}$$, …)
for mathematically obviously [beautiful](https://en.wikipedia.org/wiki/Golden_ratio) reasons.

Last but not least,
the ability to render existing pdflatex documents also with LuaLaTeX
with maybe often no or not much tweaking necessary to preserve the look,
could be very valuable for a transition to LuaLaTeX, which would, e.g.,
allow to make existing documents more accessible as tagged PDFs.

What I can say from my side is that if Fates permit,
I would like to implement this,
at first privately.

Near Zürich, Switzerland, 27 Nov 2025

Alain Stalder 

[exactphilosophy.net](https://www.exactphilosophy.net)
