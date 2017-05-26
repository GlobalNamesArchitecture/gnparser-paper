Paper about Global Names Parser
===============================

Open Access/Open Science paper about [gnparser]

This paper is published on 2017-05-26 by [BMC Bioinformatics][bmc-pub],
DOI: 10.1186/s12859-017-1663-3

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
[bmc-pub]: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1663-3
