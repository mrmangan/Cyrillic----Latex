# Cyrillic----Latex

PDF for directions: [Cryillic.pdf](https://github.com/mrmangan/Cyrillic----Latex/files/7152177/Cryillic.pdf)

Required packages and commands can be found in the tex file attached.

Required packages: 

\usepackage{newunicodechar}
\usepackage{fontspec}
\usepackage{float}
% make new environment
\usepackage[OT2,OT1]{fontenc}
\newcommand\cyr
{\renewcommand
	\rmdefault{wncyr}
	\renewcommand
	\sfdefault{wncyss}
	\renewcommand
	\encodingdefault{OT2}
	\normalfont
	\selectfont
}
\DeclareTextFontCommand{\textcyr}{\cyr}
