# Syntactic Rules 2.2

Rules are developed by Phillip Wolff, and Bridget Copley.

## Future rules:
```
ADJP < (JJ < able|enough|willing) < (S < (VP < TO < VP))  
ADJP < (JJ < likely|excited) < (S < (VP < TO < VP))
S|VP|ADJP|ADVP < (IN|RB < about) $ (S < VP < TO))
S < (RB < about) < (VP < (TO < to))
NP < (S < (VP < TO < VP))
SBAR < WHNP|WHADVP < (S < (VP < TO))
VP !< (__ < /seem|appear|happen/) < (S < ( VP < TO < VP))
VP < (PP < (IN < about|of ) !< (RB < instead) < (S < ( VP <+(VP) VBG)))
VP < (VB|VBD|VBG|VBN|VBP|VBZ < /need/) < (S < ( VP < TO))
VP < (VB|VBD|VBG|VBN|VBP|VBZ < /need/) < NP
VP < (VB|VBD|VBG|VBN|VBP|VBZ < /hav|had/) < (S < (VP < TO))
VP < (VBN < supposed) < (S < (VP < TO))
VB|VBD|VBG|VBN|VBP|VBZ < /want/
VBP < wan
S < (NP $ (RB < better) $ VP)
S < (NP $ (ADVP <<# better) $ VP)
VP < (MD < /ought/) < (S < ( VP < TO))
ROOT < (S|SQ <, (VP !< TO|S !< VBG))
ROOT < (S|SQ <, INTJ < (VP !< TO|S !< VBG))
ROOT < (S|SQ <, (NP < (NN < someone|somebody)) < (VP < VB|VBP !< TO|S !< VBG))
VBG < gon
(VBG < going) < (S < (VP < TO))
MD < will|'ll
MD < wo
MD < shall
MD < would|'d
MD < may   	
MD < might
MD < should
MD < can
MD < ca
MD < could
MD < must
VP < (MD < ca) < (VP < (VB < wait))
VP < (MD < could) < (RB < n't) < (VP < (VB < wait))
S < VP << /look/ << forward
VB|VBD|VBG|VBN|VBP|VBZ << /hope|hoping/
VB|VBD|VBG|VBN|VBP|VBZ < plan|plans|planned|planning
VB|VBD|VBG|VBN|VBP|VBZ < /choos/
VB|VBD|VBG|VBN|VBP|VBZ < /schedul/
VB|VBD|VBG|VBN|VBP|VBZ < /consider/
VP < (VB|VBD|VBG|VBN|VBP|VBZ < /figur/) < (PRT < (RP < out))
NN|NNS < need
NN|NNS << /hope/
NN|NNS < /goal/
NN|NNS < /choice/
NN|NNS < /consequence/
NN|NNS < plan|plans
NN|NNS < /schedule/
NN|JJ < due
NN|JJ < future
VBG|JJ < upcoming
JJ < imminent
JJ < future
JJ < impending
JJ < ready
JJ < potential
RB < soon
RB < ahead
RB < sometime
RB < potentially
RB < finna|funna
NN|RB < tonight               	
NN|RB < tomorrow
NP < (JJ < next) < TN|TC
NP < (JJ < coming) < TN|TC
PP  < (IN < by) < (NP < (DT < the|this) < TN|TC)
PP  < (IN < by) < (NP < (DT < the|this) !< past|last|previous < TN|TC)
PP  < (IN < by) < TN|TC
(PP  < (IN < from) < (NP|ADVP < (RB < now)))
NP < (RBR|RB|JJ < later) < (DT < this)
NP|VP < (ADVP|NP < (JJ|RB < later)) < (NP|NN < today)
PP < (IN < by) < (NP < (NP < DT) < (PP < TN|TC))
S <+ (!S) (NP < (DT < this < TN|TC)) !<< VBD !<< (VP [ < (VB < have) | < (VBP [ < have | < 've ] ) | < (VBZ [ < has | < 's ] ) ] < (VP < VBN))
S <+ (!S) (PP < (IN < in|for) < (NP <, DT|CD|JJ < TC)) !<< VBD !<< (VP [ < (VB < have) | < (VBP [ < have | < 've ] ) | < (VBZ [ < has | < 's ] ) ] < (VP < VBN))
S <+ (!S) (PP < (IN < at) < (NP < CD)) !<< VBD !<< (VP [ < (VB < have) | < (VBP [ < have | < 've ] ) | < (VBZ [ < has | < 's ] ) ] < (VP < VBN))
S <+ (!S) (PP  < (IN < on|for) < TN) !<< VBD !<< (VP [ < (VB < have) | < (VBP [ < have | < 've ] ) | < (VBZ [ < has | < 's ] ) ] < (VP < VBN))
S <+ (!S) (RB < later) !<< VBD !<< (VP [ < (VB < have) | < (VBP [ < have | < 've ] ) | < (VBZ [ < has | < 's ] ) ] < (VP < VBN))
```

## Past rules:
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
