# EDP2

Repositório público com materiais de estudo de EDP2, reunindo PDFs de aulas, listas, notas, plano de ensino e referências sobre equações diferenciais parciais, espaços de Sobolev e análise funcional.

Também há uma pequena aplicação em LaTeX em `application/a.tex`, discutindo uma aplicação do Teorema de Hahn-Banach a EDPs, soluções fracas e existência de soluções em \(L^\infty\) para a equação \(\mathrm{div}(u)=F\).

## Conteúdo

- `plano de ensino.pdf`: plano da disciplina.
- `aulas 1 a 3.pdf`, `aulas 4 a 6.pdf`, `aulas 7 a 9.pdf`, `aulas 12 a 13.pdf`: materiais de aula.
- `listas.pdf` e `ex06_sol.pdf`: listas e solução de exercício.
- `notas Mayra.pdf`, `notas parte 1.pdf`, `apostila Marcelo.pdf`, `rodney.pdf`: notas e apostilas de apoio.
- `sobolev_spaces.pdf`: referência sobre espaços de Sobolev.
- `application/a.tex`: arquivo-fonte LaTeX de uma nota sobre Hahn-Banach e EDPs.

## Compilando o LaTeX

Para gerar o PDF a partir de `application/a.tex`, use:

```bash
cd application
pdflatex a.tex
```

Ou, se disponível:

```bash
latexmk -pdf a.tex
