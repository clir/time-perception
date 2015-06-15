# Syntactic Rules 1.0

They are rules following the definition of StanfordNLP Tregex: http://nlp.stanford.edu/software/tregex.shtml

Rules are developed by Phillip Wolff and Bridget Copley

If you are using this version of the rule, please cite our paper: 

```
Nie, A., Shepard, J., Choi, J., Copley, B., & Wolff, P. (2015, June). Computational Exploration of the Linguistic Structures of Future-Oriented Expression: Classification and Categorization. In NAACL-HLT 2015 Student Research Workshop (SRW) (Vol. 867, No. 164,772, p. 168).
```

## Future

```

(VP < (VBG < going) < (S < (VP < TO)))
(VP < (VBG < going) > (PP < TO))
MD < will
MD < ‘ll’
MD < shall
MD < would
MD < 'd’
VP < VBD << would
MD < may
MD < might
MD < should
MD < can
MD < could
VP < VBD << could
MD < must
MD < ought
VB|VBD|VBG|VBN|VBP|VBZ < need|needs|needed|needing
VP [ << have | << has | << had << having ] < ( S < ( VP < TO ))
VP [ << supposed] < ( S < ( VP < TO ) )
ADJP < ( JJ [ < unable ]) < ( S < ( VP < TO ))
ADJP < ( JJ [ < able]) < ( S < ( VP < TO ))
VP < ( PP < ( IN < about|of ) < ( S < ( VP <+( VP ) VBG )))
SBAR < WHNP|WHADVP < (S < (VP < TO ))
S < ( VP < TO < ( VP < VB ))
VP [ << look | << looks | << looking]  << forward
VP << want|wants|wanted|wanting|hope|hopes|hoped|hoping
goal|goals|ambition
upcoming|future|impending
plan|plans|planned
NP << need|needs
tomorrow|soon|later
NP << (week|weekend|month|year| ,, next)
tonight
NP << (week|weekend|month|year| ,, this)
NP << this [ << ( weekend ,, this ) | << ( evening ,, this )]
IN $ (NP < CD << hours|days|weeks|months|seasons|years)
IN $ (NP < DT <<  hour|day|week|weekend|month|season|year)
JJ < next $ (NN < hour|day|week|weekend|month|season|year)
IN < CD << hour|day|week|weekend|month|season|year
```

## Past

```
VBD
VP [ < ( VB < have ) | < ( VBP [ < have | < 've ] ) | < ( VBZ [ < has | < 's ] ) ] < ( VP < VBN )
S < (when < VBD) <<  MD < would
VP [ < ( VB [ < remember | < miss | < regret | < recall | < recollect ] ) | < ( VBP [ < remember | < miss | < regret | < recall | < recollect ] ) | < ( VBZ [ < remembers | < misses | < regrets | < recalls | < recollects ] ) ] < NP
forgets|forgot|forgotten|forget !.to
VP [ < ( VB < thank ) | < ( VBP < thank ) | < ( VBZ < thanks ) | < ( VBG < thanking ) ] < ( PP < ( IN < for ) )
VP << wish|wishes|wished|wishing
NP < ( JJ|NN < past )
NP < ( NP < ( NNS [ < thanks | < congratulations | < congrats | < props | < kudos | < praise ] ) ) < ( PP < ( IN < for ) )
NP << regret|regrets
yesterday
NP < (JJ < last) < (NN < week|weekend|month|year)
NP < (JJ < last) < (NNS < weeks|weekends|months|years)
proud . of|former|previous
ago
so.far
```

## Present

```
VBZ
VBG
VBP
```
