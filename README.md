# ecobiblatex

A collaborative effort to provide biblatex files for most ecological journals.

[Biblatex](https://github.com/plk/biblatex) is a set of LaTeX macros to handle the printing of citations and references, designed to work with [biber](http://biblatex-biber.sourceforge.net/).
While it's really impressive and easy to use, there are not a lot of citation styles currently available, and this project aims to provide some for the most common ecological journals.

The list below indicates which styles are implemented in the current release.
The link refers to the instruction for authors pages.
However, the correct format was taken from the list of references in a PDF of the latest issue at the time of the commit.

## Styles currently implemented

[*Ecol. Lett.*](http://bit.ly/IdEIY5)
[*Glob. Ecol. Biogeogr.*](http://bit.ly/JoUgbk)
*British Ecological Society*
[*Trends Ecol. Evol.*](http://bit.ly/ItbUrh)
*Am. Nat.* - coming soon
*Integr. Comp. Biol.* - in progress

## TODO

- [X] Journal abbreviation
- [X] *Glob. Ecol. Biogeogr.* -> Show all authors in the references; et al. in italic
- [ ] TREE -> In references, et al. and journals must be in italic

<!--
Update biblatex compatibility as suggested by the PR of @Bisaloo for Ecol. Lett. and British Ecology Society.
Fix the following deprecated commands: firstinits to “giveninits and mkbibnamefirst to mkbibnamegiven for Ecol. Lett., Glob. Ecol. Biogeogr. and Trends Ecol. Evol.
Add TREE style from @Winawer with some adjustments.
-->
