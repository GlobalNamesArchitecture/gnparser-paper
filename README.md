Paper about Global Names Parser
===============================

Open Access/Open Science paper about [gnparser]

Introduction
------------

This is a paper in preparation about [GlobalNames][gn]. The goal is to write
the paper the same way we write code -- keep changes
under revision control, give full and early access to the data for everyone to
see. This is how we program, lets see how it works for scientific literature.

The main [text of the paper][paper] is written in latex and can be found
on GitHub.

The ``data`` supporting the conclusions of this paper are located under the
[data](directory) of this repository.

Continuous build
----------------

For linux add to .latexmkrc

```
$pdflatex = 'pdflatex -interaction=nonstopmode';
$pdf_previewer = "evince";
```

[gnparser]: https://github.com/GlobalNamesArchitecture/gnparser
[gn]: http://globalnames.org
[paper]: /gnparser.tex
[data]: https://github.com/GlobalNamesArchitecture/gnparser-paper/tree/master/data
