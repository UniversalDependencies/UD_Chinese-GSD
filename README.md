# Summary

Traditional Chinese Universal Dependencies Treebank annotated and converted by
Google.


# Changelog

* 2025-11-15 v2.17
  * Fixed attachment clf+det according to the guidelines.
* 2023-11-15 v2.13
  * Some PART/ADV should be SCONJ (see https://github.com/UniversalDependencies/docs/issues/460 and https://github.com/slavpetrov/parallel-treebanks/issues/30).
  * Fixed attachment clf+nummod according to the guidelines.
* 2023-05-15 v2.12
  * Fixed: PUNCT nodes must be attached via punct relations.
  * Fixed: Only some UPOS categories are compatible with mark.
  * Fixed: Only some UPOS categories are compatible with det.
  * Fixed: ADJ cannot be copula.
  * Fixed: Auxiliary must be tagged AUX.
  * Fixed: Nominal cannot be advmod.
  * Fixed: Verb cannot be advmod.
  * Added pinyin transcription.
  * Scaled down the set of copulas and other auxiliaries.
  * Fixed: function words must be leaves.
  * Fixed: case marker adpositions mislabled as acl.
* 2021-05-15 v2.8
  * Changed mark:relcl to mark:rel (as in the other Chinese treebanks).
  * Removed the relation case:dec (for 的 between two nouns; the other treebanks use just `case` here.
  * Removed the relation aux:aspect (the aspect particles 了 (le), 過 (guo), 著 (zhe) use just `aux` in the other treebanks).
  * Question particles changed from Mood=Inter to PartType=Int, and from discourse to discourse:sp.
  * Undocumented relation subtypes case:pref and case:suff changed to case.
  * Extent constructions converted from cop + mark:comp to compound:ext.
  * Changed mark:advb to mark:adv (as in the other Chinese treebanks).
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
Parallel: no
Genre: wiki
Lemmas: automatic with corrections
UPOS: converted from manual
XPOS: manual native
Features: automatic with corrections
Relations: converted from manual
Contributors: Shen, Mo; McDonald, Ryan; Zeman, Daniel; Qi, Peng
Contributing: here
Contact: pengqi@cs.stanford.edu
===============================================================================
</pre>
