# bibliography
Holds bibtex entries for papers

The strings.bib file contains the definitions for standard journals
and conference names.    These are in the medium-length format
(e.g. "ACM Symposium on Parallelism in Algorithms and Architecture
(SPAA)").

The main.bib file contains all the entries.

Should be used as:
\bibliography{strings,main}
In particular the strings needs to be first so it is defined for main.

PLEASE add to the main and strings file.    Try to avoid duplicates.

Unfortunately the naming convention is not consistent since entries
come from all over the place.

If someone wants to create a "shortstring.bib" file with short entries
(e.g. "SPAA") that would be great.
