# Bits, Bytes, and Binyanim

The Semantic &amp; Syntactic Datasets of Arian Verheij's Hebrew Verb Study

## Original Readme Description

```
begin of file verbdata.doc -- information on the file verbdata.bbb
A.J.C. Verheij       <arian@th.vu.nl>                February 1999
===============================================================

The file 

                       verbdata.bbb

contains the main data base used in

                      A.J.C. Verheij 
      Bits, Bytes, and Binyanim -- A Quantitative Study of 
          Verbal Lexeme Formations in the Hebrew Bible
              OLA ???, Leuven, Peeters, 1999 ????

===============================================================

You are free to use these data provided that adequate references
are given in any publication that might ensue.

You are free to make a local copy of this file under a different
name and modify it.

You are NOT allowed to distribute a modified version of this file
under its original name of verbdata.bbb.

===============================================================

The file verbdata.bbb is a UNIX-style ASCII file, containg
    3276 lines, and
    26208 strings of non-spaces. 

Size: 190920 bytes
Checksum (System V): 19219

===============================================================

DESCRIPTION

The file verbdata.bbb contains data on the 3276 verbal lexemes of the
Hebrew Bible. Each line holds one record, consisting of 8 fields.
As an example, here are the first and last lines:

>BD     01_qal        rcat=3wk dyn=y tl=y ag=n tr=n tok=119
TRGM    06_puccal     rcat=3st dyn=y tl=y ag=n tr=n tok=1

The fields that make up one record are the following (illustrated
with their realizations in the first line of the example above):


--------------------
>BD		ROOT
--------------------

	The first field of a record holds the root of the verbal lexeme.
	The root is written in the transliteration of WIT-BHS, the
	Werkgroep Informatica Text based on Biblia Hebraica 
	Stuttgartensia. The transliteration scheme is the following:

		> B G D H W Z X V J K L M N S < P Y Q R F C T

	The equal sign `=' (not in the example) is used to distinguish 
	homographs.

	For further details on WIT-BHS, see A.J.C. Verheij, 
	Grammatica Digitalis I. The Morphological Code in the
	``Werkgroep Informatica'' Computer Text of the Hebrew Bible.
	Applicatio 11. Amsterdam, VU University Press, 1994.


----------------------
01_qal		BINYAN
----------------------

	The second field holds the binyan of the lexeme. The leading
	number (in this case, `01_') serves sorting purposes.
	The binyanim that occur in the data base are the following:

	01_qal		10_pulpal	19_nupocal	28_hutpacel
	02_pqal		11_pecalcal	20_nipaccel	29_hitpocel
	03_pocel	12_pucalcal	21_nupaccel	30_hitpaccel
	04_pocal	13_ifcal	22_nipaclel	31_hutpaccal
	05_piccel	14_hifcil	23_tifcal	32_hitpaclel
	06_puccal	15_hofcal	24_tipaccel	33_hitpalpal
	07_paclel	16_nifcal	25_itpocel	34_hitpcalcal
	08_puclal	17_nufcal	26_itpaccal	35_nitpacal
	09_pilpel	18_nipocel	27_hitpacel	

	The first and second field, taken together, constitute the
	verbal lexeme (root + binyan).


-----------------------------
rcat=3wk	ROOT CATEGORY
-----------------------------

	The third field specifies the morphological category of the root
	(`rcat'). The expression `=3wk' means that the root is seen as a
	triconsonantal root with a weak consonant in it. The expressions
	used in the data base are: 
	
		3st	3wk	hol	gem


--------------------------
dyn=y		DYNAMICITY
--------------------------

	The fourth field specifies whether the verbal lexeme is dynamic
	(`dyn'). The expression `=y' means that such is considered to be
	the case. The alternative expression `=n' means that it is not
	considered to be the case.


------------------------
tl=y		TELICITY
------------------------

	The fifth field specifies whether the verbal lexeme is telic
	(`tl'). For the expression `=y', see above under Dynamicity.


--------------------------
ag=n		AGENTIVITY
--------------------------

	The sixth field specifies whether the Subject of the lexeme
	is considered to be an Agent (`ag'). For the expression `=n',
	see above under Dynamicity.


----------------------------
tr=n		TRANSITIVITY
----------------------------

	The seventh field specifies whether the lexeme is transitive,
	(`tr') which depends on its being attested in the Hebrew Bible
	with a Direct Object. For the expression `=n', see above under
	Dynamicity.


-------------------------------
tok=119 	TOKEN FREQUENCY
-------------------------------

	The eighth field specifies the token frequency (`tok') of the
	lexeme as a lexical type, i.e., the number of times that the
	lexeme occurs in the Hebrew Bible.

end of file verbdata.doc -- information on the file verbdata.bbb
```
