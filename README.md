Material para o curso MOOC de LaTeX do PoliGNU
----------------------------------------------

Arquivos-fonte para o material de referência do curso de LaTeX formato
MOOC<sup>[1](#note1)</sup> produzido pelo [PoliGNU][polignu]<sup>[2](#note2)</sup>.

<a name="note1"><sup>1</sup></a>: curso massivo aberto online, ou _Massive Online Open Course_

<a name="note2"><sup>2</sup></a>: grupo de estudos de Software e Cultura Livres da Poli-USP.

[polignu]: www.polignu.org

Para simplificar a distribuição dos módulos desagrupados, cada "item"
do material está em uma pasta.


Roteiro para video-aulas
------------------------

Tássio está escrevendo este roteiro para o curso do MOOC.

O curso deve ter entre um mês e meio e dois meses,
com ~1h30 de vídeo por semana.

## Módulo 0 &mdash; Boas vindas e introdução
- [ ] o que é, o que é? (show de exemplos)
- [ ] como usar a plataforma do MOOC (onde estão os vídeos, o fórum, como participar, perguntas e tarefas) 
- [ ] quem somos nós (PoliGNU, apresentação das pessoas)
- [ ] história e contexto (Knuth, por que o LaTeX é de graça)
- [ ] como faz? (instalação, editores de texto)

## Módulo 1 &mdash; Arroz com feijão
- [ ] texto puro! (marcação semântica, qual é a diferença?)
- [ ] produzindo um documento (partes do documento, compilação)
- [ ] os programas que vamos usar no curso (pdflatex, bibtex para bibliografia) 
- [ ] os arquivos produzidos (e pra quê servem) #mencionar que mais de uma etapa de compilação pode ser necessária
- [ ] onde buscar ajuda? (lshort, wikibooks, comunidade, tex.stackexchange, OSQA para o MOOC?)
- [ ] Erros comuns (confundir editor e compilador) 
- [ ] Tarefa e Desafio

## Módulo 2 &mdash; Escrevendo texto
- [ ] Sintaxe (texto versus comandos, cabeçalho do documento, pacotes, parâmetros)
- [ ] Pontuação, espaços (comando espaço e espaços inquebráveis), apóstrofo, traços (-, --,---). 
- [ ] Caracteres especiais
- [ ] Quebra de linha, novo parágrafo e nova página, (par, newline, noindent, newpage).
- [ ] Hifenação
- [ ] Erros comuns
- [ ] Tarefa e Desafio

## Módulo 3 &mdash; Formatando Texto
- [ ] Ambientes (centralizado, alinhado, à esquerda, quote, quotation, etc.) #enfatizar que begin e end são comandos
- [ ] Mais ambientes (itemize, enumerate,description) # items com parâmetro opcional em description, enumerate tem parâmetro opcional também
- [ ] Nota de rodapé e nota marginal (footnote, agrupamentos)
- [ ] Novos comandos (abreviações)
- [ ] Formatação básica (ênfase, negrito, sem serifa, versalete) #retomar agrupamentos
- [ ] Formatação básica (normalsize, large, Large, huge small, tiny, footnotesize) #retomar agrupamentos
- [ ] Comandos com parâmetros (exemplo: comentários destacados usando cores!)
- [ ] Erros comuns
- [ ] Tarefa e Desafio

## Módulo 4 &mdash; Seções, Figuras, Tabelas, Rótulos e numerações
- [ ] Primeiro capítulo (capítulos, seções, subseções, tableofcontents, label e ref)
- [ ] Figuras (includegraphics, ambiente figure, caption, label, ref, listoffigures) # novo comando faltafig
- [ ] Tabelas (tabular, colunas e linhas, alinhamento, table, listoftables)
- [ ] Tabelas (linhas verticais e horizontais, separadores de colunas)
- [ ] Tabelas(multirow e multicol)
- [ ] Pacote útil: hyperref
- [ ] Erros comuns
- [ ] Tarefa e Desafio

## Módulo 5 &mdash; Mais formatação de texto, espaçamento e contadores
- [ ] Outros comandos úteis (url, selectfont, doublespacing, onehalfspacing, rule)
- [ ] Espaçamento vertical (smallskip, medskip, bigskip, vspace, vspace*)
- [ ] Espaçamento horizontal (hspace, quad, thinspace, neg)
- [ ] Novos ambientes
- [ ] Contadores (newcounter, stepcounter, refstepcounter, questões numeradas)
- [ ] Ambientes com parâmetros (exemplo, anotações de autores, diálogos)
- [ ] Erros comuns
- [ ] Tarefa e Desafio


## Módulo 6 &mdash; formatando a página
- [ ] Opções da classe de documento (a4paper, 12pt, article, twoside, twocolumn)
- [ ] estilos de capítulo (chapterstyle) e estilo de página
- [ ] cabeçalho e rodapé (page, lastpage)
- [ ] margens do documento (setlrmargins, setulmargins, checkandfixthelayout)
- [ ] Erros comuns
- [ ] Tarefa e Desafio


## Módulo 7 &mdash; Matemática
- [ ] dois tipos de expressões (inline e display)
- [ ] operações e comparações (+ - / times cdot sqrt, sin log cos tan DeclareMathOperator)
- [ ] expoente, índice, sum, prod, lim int
- [ ] frações, binomial e delimitadores (frac, binom left right combinados com barra, parênteses chaves e colchetes)
- [ ] matrizes (array)
- [ ] texto e espaçamento (quad, text,  \!, \, \: \;, integrais) #comando para dx
- [ ] casos (cases)
- [ ] letras gregas
- [ ] vetores e acentos (vec, bar, tilde, hat, widetilde, widehat)
- [ ] outras fontes (mathbf, mathrm, mathbb)
- [ ] operações com conjuntos (in, notin, subset, subseteq, supset, supseteq)
- [ ] equações numeradas (equation, align)
- [ ] overbrace e underbrace
- [ ] Erros comuns
- [ ] Tarefa e Desafio

## Módulo 8 &mdash; Bibliografia
- [ ] Bibliografia no muque (thebibliography, bibitem)
- [ ] BibTeX (resultado, fluxo de trabalho) # exemplo com artigos
- [ ] BibTeX outros tipos de entradas, plain vs alpha
- [ ] Erros comuns
- [ ] Tarefa e Desafio

## Outros assuntos
- microtype
- multicol
- verbatim
- ABNTeX
- índices remissivos
- glossário
- syntax highlight
- algoritmos
- fórmulas químicas(chemfig)
- diagramas (tikz)
- gráficos (pgfplots)
- natbib

Notas
-----

O material na pasta `aulas-anteriores` está sendo reorganizado,
e os arquivos devem mudar para alguma pasta em breve.

Licença
-------

Este material é distribuído sob a licensa GNU FDL 1.3 ou superior
(veja arquivo `fdl-1.3.txt`).

Copyright (C) 2014
  PoliGNU
Distribuído sobre a licensa GNU FDL 1.3 ou superior, veja arquivo
fdl-1.3.txt

Notas de desenvolvimento
------------------------

Este repositório costumava ser guardado em 

    git@gitorious.org:material-latex-mooc-polignu/material-latex-mooc-polignu.git (fetch)
    git@gitorious.org:material-latex-mooc-polignu/material-latex-mooc-polignu.git (push)originorigin
