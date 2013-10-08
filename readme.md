# mrg_docs
This is the documentation for the [MRG MATLAB toolbox][mrg]. The contents of this repository are probably best browsed directly at the [MRG toolbox documentation pages][mrg_docs]. It is hosted here in a separate repository (not in an orphaned `gh-pages` branch, like GitHub [recommends][gh_docs]) because MATLAB insists on locking files (on Windows), which makes branch-switching in git a real pain.

## How?
The documentation itself is generated dynamically from the code using the brilliant [m2html][m2html] toolbox by Guillaume Flandin, using the following command:

`m2html('mfiles', 'mrg', 'htmldir', 'mrg_docs', 'recursive', 'on', 'todo', 'on', 'template', 'blue')`

## Licence
This information is provided to support the MRG MATLAB toolbox and as such, the everything that applies there also extends to this documentation.  Please [read the information][mrg] associated with that repository for more information.  

[m2html]: http://www.artefact.tk/software/matlab/m2html
[mrg]: https://github.com/dpritchard/mrg#readme
[mrg_docs]: http://dpritchard.github.io/mrg_docs
[gh_docs]: https://help.github.com/articles/creating-project-pages-manually

