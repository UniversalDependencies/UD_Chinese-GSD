# Summary

Traditional Chinese Universal Dependencies Treebank annotated and converted by
Google.


# Changelog

* 2021-05-15 v2.8
  * Changed mark:relcl to mark:rel (as in the other Chinese treebanks).
* 2020-11-15 v2.7
  * Aspect markers relations are corrected from `case:aspect` to `aux:aspect`.
* 2019-11-15 v2.5
  * Google gave permission to drop the "NC" restriction from the license.
    This applies to the UD annotations (not the underlying content, of which Google claims no ownership or copyright).
  * Fixed punctuation (use East Asian punctuation where appropriate)
  * Fixed various parses and features (e.g., added Case=Ord)
  * Some manual fixes in tokenization
2017-03-01 v2.0
  * Conversion to UD v2 by Dan Zeman.
  * Added SpaceAfter=No.
  * Added lemmas.
  * Case=Advb,Comp,Rel changed to deprel mark:advb/comp/relcl.
  * Detected classifiers, changed their deprel to clf.
2016-11-15 v1.4
  * No changes since UD release 1.3.
2016-05-15 v1.3
  * Initial UD release.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v1.3
License: CC BY-SA 4.0
Includes text: yes
Genre: wiki
Lemmas: automatic
UPOS: converted from manual
XPOS: manual native
Features: automatic with corrections
Relations: converted from manual
Contributors: Shen, Mo; McDonald, Ryan; Zeman, Daniel; Qi, Peng
Contributing: here
Contact: pengqi@cs.stanford.edu
===============================================================================
</pre>
