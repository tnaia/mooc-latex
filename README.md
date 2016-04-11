Material para o curso MOOC de LaTeX do PoliGNU
----------------------------------------------

Arquivos-fonte para o material de referência do curso de LaTeX formato
MOOC<sup>[1](#note1)</sup> produzido pelo [PoliGNU][polignu]<sup>[2](#note2)</sup>.

<a name="note1"><sup>1</sup></a>: curso massivo aberto online, ou _Massive Online Open Course_.

<a name="note2"><sup>2</sup></a>: grupo de estudos de Software e Cultura Livres da Poli-USP.

[polignu]: www.polignu.org

Para simplificar a distribuição dos módulos desagrupados, cada "item"
do material está em uma pasta.

Próximos passos
---------------

1. [ ] [episódios-piloto](https://www.youtube.com/watch?v=J3R6HR0scCM&list=PLUOUidAXN8Oa8F81TKxJhVnDCIdHe9uhO)
2. [ ] gravar/editar os vídeos (versão final)
3. [ ] polir o material didático
4. [ ] bolar as questões, tarefas e desafios
5. [ ] carregar o material no EdX
6. [ ] oferecer o curso!

Roteiro para video-aulas
------------------------

O curso terá entre um mês e meio e dois meses,
com ~1h30 de vídeo por semana.

Os dois primeiros módulos são liberados na primeira semana.

## Módulo 0 &mdash; Boas vindas e introdução
1. [ ] o que é, o que é? (show de exemplos, o que vamos cobrir no curso)
2. [ ] como usar a plataforma do MOOC (onde estão os vídeos, o fórum,
 como participar, perguntas e tarefas) 
3. [ ] quem somos nós (PoliGNU, apresentação das pessoas)
4. [x] [história e contexto (Knuth, por que o LaTeX é de graça)](https://youtu.be/FEz0qYls9SI?list=PLUOUidAXN8Ob28rdtr0awBEHv3lvCtKGp)
5. [ ] como faz? (instalação, editores de texto)

## Módulo 1 &mdash; Arroz com feijão
1. [x] [texto puro! (marcação semântica, qual é a diferença?)](https://youtu.be/buBmazofm3s)
2. [x] [produzindo um documento (texmaker, partes do documento, compilação)](https://youtu.be/ZEEpMzfLF1c)
3. [ ] os programas que vamos usar no curso (texmaker, pdflatex, bibtex) 
4. [ ] os arquivos produzidos (e pra quê servem)
 falar que mais de uma etapa de compilação pode ser necessária
5. [ ] onde buscar ajuda? (lshort, wikibooks, comunidade,
 tex.stackexchange, OSQA para o MOOC?)
6. [ ] Erros comuns (confundir editor e compilador) 
7. [ ] Tarefa e Desafio

## Módulo 2 &mdash; Escrevendo texto
1. [ ] Sintaxe (texto versus comandos, cabeçalho do documento,
 pacotes, parâmetros)
2. [ ] Pontuação, espaços (comando espaço e espaços inquebráveis),
 apóstrofo, traços (-, --,---). 
3. [ ] Caracteres especiais
4. [ ] Quebra de linha, novo parágrafo e nova página, (par, newline,
 noindent, newpage).
5. [ ] Hifenação
6. [ ] Erros comuns
7. [ ] Tarefa e Desafio

## Módulo 3 &mdash; Formatando Texto
1. [ ] Ambientes (centralizado, alinhado, à esquerda, quote, quotation, etc.)
 destacar que begin e end são comandos
2. [ ] Mais ambientes (itemize, enumerate,description)
 items com parâmetro opcional em description, enumerate tem parâmetro
 opcional também
3. [ ] Nota de rodapé e nota marginal (footnote, agrupamentos)
4. [ ] Novos comandos (abreviações)
5. [ ] Formatação básica (ênfase, negrito, sem serifa, versalete)
 retomar agrupamentos
6. [ ] Formatação básica (normalsize, large, Large, huge small,
 tiny, footnotesize) #retomar agrupamentos
7. [ ] Comandos com parâmetros (exemplo: comentários destacados usando cores!)
8. [ ] Erros comuns
9. [ ] Tarefa e Desafio

## Módulo 4 &mdash; Seções, Figuras, Tabelas, Rótulos e numerações
1. [ ] Primeiro capítulo (capítulos, seções, subseções, tableofcontents, label e ref)
2. [ ] Figuras (includegraphics, ambiente figure, caption, label, ref, listoffigures) # novo comando faltafig
3. [ ] Tabelas (tabular, colunas e linhas, alinhamento, table, listoftables)
4. [ ] Tabelas (linhas verticais e horizontais, separadores de colunas)
5. [ ] Tabelas(multirow e multicol)
6. [ ] Pacote útil: hyperref
7. [ ] Erros comuns
8. [ ] Tarefa e Desafio

## Módulo 5 &mdash; Mais formatação de texto, espaçamento e contadores
1. [ ] Outros comandos úteis (url, selectfont, doublespacing, onehalfspacing, rule)
2. [ ] Espaçamento vertical (smallskip, medskip, bigskip, vspace, vspace*)
3. [ ] Espaçamento horizontal (hspace, quad, thinspace, neg)
4. [ ] Novos ambientes
5. [ ] Contadores (newcounter, stepcounter, refstepcounter, questões numeradas)
6. [ ] Ambientes com parâmetros (exemplo, anotações de autores, diálogos)
7. [ ] Erros comuns
8. [ ] Tarefa e Desafio


## Módulo 6 &mdash; formatando a página
1. [ ] Opções da classe de documento (a4paper, 12pt, article, twoside, twocolumn)
2. [ ] estilos de capítulo (chapterstyle) e estilo de página
3. [ ] cabeçalho e rodapé (page, lastpage)
4. [ ] margens do documento (setlrmargins, setulmargins, checkandfixthelayout)
5. [ ] Erros comuns
6. [ ] Tarefa e Desafio


## Módulo 7 &mdash; Matemática
1.  [ ] dois tipos de expressões (inline e display)
2.  [ ] operações e comparações (+ - / times cdot sqrt, sin log cos tan DeclareMathOperator)
3.  [ ] expoente, índice, sum, prod, lim int
4.  [ ] frações, binomial e delimitadores (frac, binom left right combinados com barra, parênteses chaves e colchetes)
5.  [ ] matrizes (array)
6.  [ ] texto e espaçamento (quad, text,  \!, \, \: \;, integrais) #comando para dx
7.  [ ] casos (cases)
8.  [ ] letras gregas
9.  [ ] vetores e acentos (vec, bar, tilde, hat, widetilde, widehat)
10. [ ] outras fontes (mathbf, mathrm, mathbb)
11. [ ] operações com conjuntos (in, notin, subset, subseteq, supset, supseteq)
12. [ ] equações numeradas (equation, align)
13. [ ] overbrace e underbrace
14. [ ] Erros comuns
15. [ ] Tarefa e Desafio

## Módulo 8 &mdash; Bibliografia
1. [ ] Bibliografia no muque (thebibliography, bibitem)
2. [ ] BibTeX (resultado, fluxo de trabalho) # exemplo com artigos
3. [ ] BibTeX outros tipos de entradas, plain vs alpha
4. [ ] Erros comuns
5. [ ] Tarefa e Desafio

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

Lembretes
---------

- [ ] Questionário na inscrição
 - você já usou LaTeX?
 - você conhece software livre?
 - qual a sua área de atuação
- [ ] Fazer um questionário ao fim do curso
 - quais as duas melhores coisas do curso?
 - e as duas piores?
 - o que você mais gostou de fazer?
 - o que não funcionou bem?
 - o que poderia ter sido melhor
 - o que você gostaria de aprender mas não foi coberto?
 - que outros cursos você gostaria que fossem oferecidos?
 - qual a sua opinião sobre software livre? (marque os que se aplicam)
  - [ ] prefiro não usar
  - [ ] indiferente
  - [ ] gostei, interessante
  - [ ] estou recomendando para outras pessoas
  - [ ] é a minha primeira escolha

Notas
-----

O material na pasta `aulas-anteriores` está sendo reorganizado,
e os arquivos devem mudar para alguma pasta em breve.

Agradecimentos
--------------

O curso de LaTeX do PoliGNU (em suas diversas encarnações) não teria
sido possível sem a dedicação de várias pessoas.


- Darnerson Pereira de Sousa
- Diego Rabatone de Oliveira
- Felipe Pait
- Haydée Svab
- Michelle Sena
- Moisés Medeiros de Oliveira
- Rodrigo Rodrigues da Silva
- Shayenne da Luz Moura
- Tássio Naia
- Thiago "tecepe" Costa de Paiva
- Vitor Matosinho Martins

Se o seu nome está faltando na lista, escreva para a gente!


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

