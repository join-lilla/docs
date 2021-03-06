---
layout: base
title:  'Universal Dependencies --- Syntactic validation'
udver:  '2'
---

Regenerated <time class="timeago" datetime="2018-07-05T09:37:44Z">2018-07-05T09:37:44 zulu</time>

# Aux chain

Auxiliary dependencies should not form a chain.

Search expression: `_ <aux|<aux:pass|<cop (_ <aux|<aux:pass|<cop _)`

Correct example:

~~~ sdparse

Do you think that he will have left when we come ?
aux(think, Do)
aux(left, will)
aux(left, have)

~~~


Incorrect example:

~~~ sdparse

Do you think that he will have left when we come ?
aux(think, Do)
aux(have, will)
aux(left, have)

~~~


<a href="http://universaldependencies.org/u/dep/aux_.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>AUX</th><th>CCONJ</th><th>PART</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">126</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">611</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">2</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">2559</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">49</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">132 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">617 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">2560 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">49 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+%28_+%3Caux%7C%3Caux%3Apass%7C%3Ccop+_%29&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Flat is right-headed

Flat relations should be left-headed, not right.

Search expression: `_ <flat@R _`

Correct example:

~~~ sdparse

Carl XVI Gustaf
flat(Carl, XVI)
flat(Carl, Gustaf)

~~~


Incorrect example:

~~~ sdparse

Carl XVI Gustaf
flat(Gustaf, XVI)
flat(Gustaf, Carl)

~~~


<a href="http://universaldependencies.org/u/dep/flat.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>PROPN</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cflat%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cflat%40R+_&db=UD_Afrikaans-dev">20</a></td>
</tr>
<tr><td>UD_Bambara</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cflat%40R+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cflat%40R+_&db=UD_Bambara-dev">1</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cflat%40R+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cflat%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cflat%40R+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cflat%40R+_&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cflat%40R+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
</div>


# Fixed is right-headed

Fixed expressions should be left-headed, not right.

Search expression: `_ <fixed@R _`

Correct example:

~~~ sdparse

He cried because of you
fixed(because, of)

~~~


Incorrect example:

~~~ sdparse

He cried because of you
fixed(of, because)

~~~


<a href="http://universaldependencies.org/u/dep/fixed.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PRON</th><th>PUNCT</th><th>SCONJ</th><th>VERB</th> </tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed%40R+_&db=UD_Dutch-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed%40R+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cfixed%40R+_&db=UD_Dutch-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed%40R+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cfixed%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cfixed%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed%40R+_&db=UD_Portuguese-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed%40R+_&db=UD_Portuguese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed%40R+_&db=UD_Portuguese-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed%40R+_&db=UD_Portuguese-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cfixed%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed%40R+_&db=UD_Portuguese-dev">82</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cfixed%40R+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cfixed%40R+_&db=UD_Portuguese-dev">4</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cfixed%40R+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed%40R+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed%40R+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed%40R+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cfixed%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cfixed%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed%40R+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">148 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed%40R+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed%40R+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed%40R+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
</div>


# Fixed chain

Fixed dependencies should not be chained. All dependents should be attached directly to the first one.

Search expression: `_ <fixed (_ <fixed _)`

<a href="http://universaldependencies.org/u/dep/fixed.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADP</th><th>ADV</th><th>DET</th><th>NOUN</th><th>PRON</th><th>PUNCT</th> </tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">2</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">122 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cfixed+%28_+%3Cfixed+_%29&db=UD_Russian-dev">Go to search</a><p/>
</div>
</div>


# Conj is right-headed

Coordination dependencies should be left-headed, not right.

Search expression: `_ <conj@R _`

Correct example:

~~~ sdparse

Bill is big and honest
conj(big, honest)

~~~


Incorrect example:

~~~ sdparse

Bill is big and honest
conj(honest, big)

~~~


<a href="http://universaldependencies.org/u/dep/conj.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>CCONJ</th><th>DET</th><th>INTJ</th><th>NOUN</th><th>NUM</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Afrikaans-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Afrikaans-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Afrikaans-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Afrikaans-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Afrikaans-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Dutch-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Hungarian-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Hungarian-dev">27</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Hungarian-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Hungarian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Hungarian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Portuguese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Russian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cconj%40R+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cconj%40R+_&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">13 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">85 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cconj%40R+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
</div>


# Appos is right-headed

Apposition dependencies should be left-headed, not right.

Search expression: `_ <appos@R _`

Correct example:

~~~ sdparse

Sam , my brother , arrived
appos(Sam, brother)

~~~


Incorrect example:

~~~ sdparse

Sam , my brother , arrived
appos(brother, Sam)

~~~


<a href="http://universaldependencies.org/u/dep/appos.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Basque-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Bulgarian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Catalan-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Chinese-dev">488</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Chinese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Chinese-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Chinese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Chinese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Chinese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Chinese-dev">3</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Hungarian-dev">42</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Indonesian-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Indonesian-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Korean-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Korean-dev">175</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Korean-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Korean-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Russian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Russian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Serbian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Serbian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Spanish-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Spanish-dev">43</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Spanish-dev">57</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Spanish-dev">6</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">59</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos%40R+_&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos%40R+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">17 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">597 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">42 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">44 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">194 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">125 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">65 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos%40R+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Copula is not AUX

Verbal copulas should be tagged AUX, not VERB. Pronouns can also serve as copulas. Punctuation (dashes) and nouns are not copulas.

Search expression: `(!(AUX|PRON)) <cop _`

<a href="http://universaldependencies.org/docs/u/dep/cop.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>CCONJ</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PROPN</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Afrikaans-dev">28</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Ancient_Greek-dev">1864</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Basque-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Catalan-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Catalan-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Catalan-dev">38</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Chinese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Coptic-dev">19</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Coptic-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Latin-dev">363</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Russian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Serbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Spanish-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Spanish-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Spanish-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Spanish-dev">6250</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Spanish-dev">5</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Spanish-AnCora-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Spanish-AnCora-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Spanish-AnCora-dev">39</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Spanish-AnCora-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ccop+_&db=UD_Vietnamese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ccop+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">28 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">1864 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">45 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">19 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">363 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">6315 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">58 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">12 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21%28AUX%7CPRON%29%29+%3Ccop+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# PRON or DET is mark

Pronouns must not be attached using the mark relation. Relative pronouns must not be confused with subordinating conjunctions, even if the word is ambiguous.

Search expression: `(PRON|DET) <mark _`

Correct example:

~~~ sdparse

This is a fact that we cannot ignore . You know that we cannot ignore it .
dobj(ignore-8, that-5)
mark(ignore-15, that-12)

~~~


Incorrect example:

~~~ sdparse

This is a fact that we cannot ignore .
mark(ignore-8, that-5)

~~~


<a href="http://universaldependencies.org/docs/u/dep/mark.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">18 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">191 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">17 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">49 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">12 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">19 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">65 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">70 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">18 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">38 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29+%3Cmark+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
</div>


# Relation det is used for node that is neither DET nor PRON

The det relation is primarily intended for determiners, i.e. words tagged DET. Pronouns are tolerated at least until the borderline between the two classes is better investigated and defined.

Search expression: `(!DET&!PRON) <det _`

<a href="http://universaldependencies.org/docs/u/dep/det.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">869 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">2996 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">404 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">585 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">81 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">57 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">57 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">21 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">886 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21DET%26%21PRON%29+%3Cdet+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Relation punct is used for node that is not PUNCT

Only nodes tagged PUNCT can be attached using the punct relation.

Search expression: `!PUNCT <punct _`

<a href="http://universaldependencies.org/u/dep/punct.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">16 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">34 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">270 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">16 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">415 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">92 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">41 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">131 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21PUNCT+%3Cpunct+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# PUNCT is attached as neither punct nor root

Nodes tagged PUNCT can only be attached using the punct relation (and exceptionally, if it is the only node in the sentence, also root).

Search expression: `PUNCT (<!punct&<!root) _`

<a href="http://universaldependencies.org/u/dep/punct.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">13 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">19 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">175 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">57 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">24 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">1110 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">24 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">79 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">18 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3C%21punct%26%3C%21root%29+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# PRON or DET lacks the PronType feature

All pronouns and determiners should be further categorized using the PronType feature. Other POS may or may not have this feature.

Search expression: `(PRON|DET)&!PronType`

<a href="http://universaldependencies.org/docs/u/feat/PronType.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">24464 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">4305 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">81 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">6598 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">3073 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">542 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">24990 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">42 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">926 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">1839 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">1216 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">2459 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">9 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">3520 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">1832 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">6421 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">216 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">328 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">691 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28PRON%7CDET%29%26%21PronType&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# NUM lacks the NumType feature

All numerals should be further categorized using the NumType feature. Other POS may or may not have this feature.

Search expression: `NUM&!NumType`

<a href="http://universaldependencies.org/docs/u/feat/NumType.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">218 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">230 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">22 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">4053 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">32 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">3634 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">186 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">1573 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">3863 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">31 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM%26%21NumType&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
</div>


# VERB lacks the VerbForm feature

All verbs should be further categorized using the VerbForm feature. Other POS may or may not have this feature. (Note that AUX may include non-verbs, thus we cannot generally extend this test to auxiliaries.)

Search expression: `(VERB)&!VerbForm`

<a href="http://universaldependencies.org/docs/u/feat/VerbForm.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">6352 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">18673 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">1410 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">12202 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">17494 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">18517 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">9 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">105 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">3782 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">648 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">2534 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">8582 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VERB%29%26%21VerbForm&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Finite verb is not a verb

Only non-finite VerbForms are expected to appear with non-verb parts of speech (NOUN, ADJ, ADV).

Search expression: `(VerbForm=Fin)&!(VERB|AUX)`

<a href="http://universaldependencies.org/docs/u/feat/VerbForm.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21%28VERB%7CAUX%29&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21%28VERB%7CAUX%29&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21%28VERB%7CAUX%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21%28VERB%7CAUX%29&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21%28VERB%7CAUX%29&db=UD_Urdu-dev">Go to search</a><p/>
</div>
</div>


# Finite verb lacks the Mood feature

All finite verb forms should be further categorized using the Mood feature.

Search expression: `(VerbForm=Fin)&!Mood`

<a href="http://universaldependencies.org/docs/u/feat/Mood.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">375 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21Mood&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">19344 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21Mood&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21Mood&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">1079 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28VerbForm%3DFin%29%26%21Mood&db=UD_Spanish-dev">Go to search</a><p/>
</div>
</div>


# Degree feature used with a word that is neither adjective nor adverb

The Degree feature is normally associated with (a subset of) adjectives and adverbs. Other tags than ADJ and ADV are probably wrong.

Search expression: `Degree&!ADJ&!ADV`

<a href="http://universaldependencies.org/u/feat/Degree.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">23 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">2961 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">90 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=Degree%26%21ADJ%26%21ADV&db=UD_Spanish-dev">Go to search</a><p/>
</div>
</div>


# Maximum one subject

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> No predicate can have more than one subject. Note that subordinate clauses do not head copulas for this reason.

Search expression: `_ >nsubj|>csubj|>nsubj:pass|>csubj:pass _ >nsubj|>csubj|>nsubj:pass|>csubj:pass _`

<a href="http://universaldependencies.org/u/dep/nsubj.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>DET</th><th>INTJ</th><th>NOUN</th><th>NUM</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">255</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">31</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">142</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">61</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">79</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">68</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">287</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">26</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">288</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">37</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">46</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">1</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">47</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">55</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">67</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">257 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">22 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">37 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">218 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">90 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">75 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">41 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">96 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">385 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">403 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">22 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">47 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">59 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">98 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">84 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">80 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_+%3Ensubj%7C%3Ecsubj%7C%3Ensubj%3Apass%7C%3Ecsubj%3Apass+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Maximum one object

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> No predicate can have more than one direct object. Ccomp counts as direct object. (To certain extent xcomp does too, but dobj can co-occur with xcomp in cases of secondary predication, thus this test does not look at xcomp.)

Search expression: `_ >obj|>ccomp _ >obj|>ccomp _`

<a href="http://universaldependencies.org/u/dep/obj.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>VERB</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">119</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">652</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">33</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">5</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">25</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">54</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">29</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">37</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">31</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">5584</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">242</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">82</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">159</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">16</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">147</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">23</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">114</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">86</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">59</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">1</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">20</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">79</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">40</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">162</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">85</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">46</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">34</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">4781</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">6</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">94</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">519</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">129 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">661 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">37 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">25 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">5779 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">242 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">82 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">170 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">16 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">154 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">23 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">119 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">95 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">63 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">82 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">40 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">166 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">4993 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">104 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">533 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eobj%7C%3Eccomp+_+%3Eobj%7C%3Eccomp+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# NOUN and case

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> A word marked as a NOUN should not be a case dependency.

Search expression: `NOUN <case _`

<a href="http://universaldependencies.org/docs/u/dep/case.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>NOUN</th> </tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Ancient_Greek-dev">10</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Basque-dev">10</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Belarusian-dev">1</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Catalan-dev">340</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Coptic-dev">2</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Dutch-dev">3</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Hungarian-dev">2</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Korean-dev">14</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Romanian-dev">57</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Russian-dev">2</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Serbian-dev">2</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Slovak-dev">6</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Spanish-dev">91</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Spanish-AnCora-dev">326</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Swedish-dev">3</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Urdu-dev">42</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Vietnamese-dev">1</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">340 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">57 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">91 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">326 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">42 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Ccase+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# ADP is not leaf

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> By default adposition is a leaf node attached to a nominal as case. Exceptions where adpositions are not leaves involve technical relations such as mwe and conj.

Search expression: `ADP >!conj&>!cc&>!punct&>!fixed _`

<a href="http://universaldependencies.org/docs/u/dep/case.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">251 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">119 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">526 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">383 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">244 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">186 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">12 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">53 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">30 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">161 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">139 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">142 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">168 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">198 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">407 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">101 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">357 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">260 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3E%21conj%26%3E%21cc%26%3E%21punct%26%3E%21fixed+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Appos chain

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Apposition dependencies should not be chained. Multiple appositions should all be attached to the head, or they should be coordinated (with the first apposition as the head). Legitimate exceptions do occur, however, in the rare case when an apposition has an apposition of its own, which does not apply to head of the first apposition.

Search expression: `_ <appos (_ <appos _)`

Correct example:

~~~ sdparse

Sam , my brother , John 's cousin , arrived
appos(Sam, brother)
appos(Sam, cousin)

~~~


Incorrect example:

~~~ sdparse

Sam , my brother , John 's cousin , arrived
appos(Sam, brother)
appos(brother, cousin)

~~~


<a href="http://universaldependencies.org/u/dep/appos.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>CCONJ</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">219</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">69</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">204</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">15</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">42</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">1</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">26</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">534</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">79</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">110</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">2</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">1</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">19</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">66</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">92</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">1</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">127</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">75</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">384</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">53</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">145</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">32</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">202</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">3</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">498 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">29 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">63 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">582 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">202 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">194 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">663 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">390 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cappos+%28_+%3Cappos+_%29&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Relation advmod used for node that is not ADV

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Advmod is intended only for adverbs. Modifiers that are called adverbial in some traditional grammars, but are in fact prepositional or noun phrases, should be attached as nmod.

Search expression: `(!ADV) <advmod _`

<a href="http://universaldependencies.org/docs/u/dep/advmod.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">206 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">16624 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">2585 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">97 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">1466 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">2496 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">888 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">189 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">2783 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">762 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">1887 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">74 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">2353 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">1488 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">220 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">3253 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">1103 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">433 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">846 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">5374 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">369 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">3953 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">679 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">17 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">21 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">9875 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">3332 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21ADV%29+%3Cadvmod+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Heads of an advmod are nominal

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> The heads of an adverbial modifier should normally not be nominal (noun, proper noun, numeral, or pronoun). Exceptions occur in nominal clauses, where a nominal is the main predicate and can therefore take clause adverbials. Example: This is probably an exception.

Search expression: `_ <advmod (NOUN|PROPN|NUM|PRON)`

<a href="http://universaldependencies.org/docs/u/dep/advmod.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>DET</th><th>INTJ</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SCONJ</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">124</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">76</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1700</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">215</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">217</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">67</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1324</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">77</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">33</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">1</a></td>
</tr>
<tr><td>UD_Bambara</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">19</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">32</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">30</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">41</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">1052</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">101</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">39</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">172</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">2086</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">32</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">21</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">1</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">245</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">58</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">68</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">1</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">108</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">470</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">58</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">644</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">71</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">26</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">301</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">208</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">46</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">67</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">490</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">145</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">164</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">114</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">1554</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">1</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">208</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">1333</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">304</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">55</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">87</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">239</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">170</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">75</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">521</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">35</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">30</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">80</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">67</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">486</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">59</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">56</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">241</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">8</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">77</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">1943</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">82</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">29</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">3</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">32</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">339</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">2311</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">63</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">47</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">56</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">989</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">111</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">33</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">48</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">47</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">208</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">21</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">86</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">70</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">2</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">54</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">315</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">131 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">3726 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">71 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">45 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">1212 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">2404 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">321 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">94 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">593 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">58 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">776 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">592 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">70 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">642 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">325 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">1596 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">2039 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">501 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">603 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">147 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">851 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">2171 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">2831 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">1175 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">37 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">512 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">376 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cadvmod+%28NOUN%7CPROPN%7CNUM%7CPRON%29&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Acl not dependent on NOUN/PROPN/PRON/DET

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Clausal modifiers of nouns should depend on NOUN/PROPN only; those in the following table depend on other parts of speech.

Search expression: `!NOUN&!PROPN&!PRON&!DET >acl _`

<a href="http://universaldependencies.org/u/dep/acl.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>INTJ</th><th>NUM</th><th>PART</th><th>PUNCT</th><th>SCONJ</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Ancient_Greek-dev">153</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Ancient_Greek-dev">28</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Ancient_Greek-dev">27</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Basque-dev">35</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Basque-dev">26</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Basque-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Basque-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Basque-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Basque-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Belarusian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Bulgarian-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Bulgarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Bulgarian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Catalan-dev">149</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Catalan-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Catalan-dev">46</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Catalan-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Catalan-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Catalan-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Catalan-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Chinese-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Chinese-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Chinese-dev">261</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Chinese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Chinese-dev">2758</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Chinese-dev">13</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Coptic-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Coptic-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Coptic-dev">1</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Dutch-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Dutch-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Dutch-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Dutch-dev">4</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Hungarian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Hungarian-dev">28</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Indonesian-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Indonesian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Indonesian-dev">294</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Japanese-dev">345</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Japanese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Japanese-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Japanese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Japanese-dev">87</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Japanese-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Japanese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Japanese-dev">2787</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Japanese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Kazakh-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Latin-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Latin-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Latin-dev">2</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Portuguese-dev">40</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Portuguese-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Portuguese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Portuguese-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Portuguese-dev">3</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Romanian-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Romanian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Romanian-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Romanian-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Romanian-dev">1</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Russian-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Russian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Russian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Russian-dev">37</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Serbian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Serbian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Serbian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Slovak-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Slovak-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Slovak-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Slovak-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Slovak-dev">5</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Slovenian-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Slovenian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Slovenian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Slovenian-dev">2</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Spanish-dev">70</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Spanish-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Spanish-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Spanish-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Spanish-dev">2658</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Spanish-dev">11</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Spanish-AnCora-dev">324</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Spanish-AnCora-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Spanish-AnCora-dev">43</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Spanish-AnCora-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Spanish-AnCora-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Swedish-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Swedish-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Swedish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Swedish-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eacl+_&db=UD_Urdu-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eacl+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eacl+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eacl+_&db=UD_Urdu-dev">396</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Eacl+_&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">210 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">95 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">32 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">251 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">3082 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">36 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">37 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">334 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">3249 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">23 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">85 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">58 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">58 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">37 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">29 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">2775 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">400 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">18 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">407 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NOUN%26%21PROPN%26%21PRON%26%21DET+%3Eacl+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
</div>


# Marked as NUM but not nummod, nmod or compound

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> If a word is marked as a numeral (POS), then it should be marked as being a nummod, compound or nmod dependency. Exceptions occur when the numeral is promoted to a higher function through ellipis. Example: Take five!

Search expression: `NUM (<!nummod&<!nmod&<!compound) _`

<a href="http://universaldependencies.org/docs/u/pos/NUM.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>NUM</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Afrikaans-dev">56</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Ancient_Greek-dev">26</a></td>
</tr>
<tr><td>UD_Bambara</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Bambara-dev">1</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Basque-dev">2305</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Belarusian-dev">86</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Bulgarian-dev">255</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Catalan-dev">2254</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Chinese-dev">333</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Coptic-dev">27</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Dutch-dev">1583</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Hungarian-dev">609</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Indonesian-dev">261</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Japanese-dev">1282</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Kazakh-dev">206</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Korean-dev">125</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Latin-dev">52</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Portuguese-dev">895</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Romanian-dev">1305</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Russian-dev">1217</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Serbian-dev">978</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Slovak-dev">439</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Slovenian-dev">295</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Spanish-dev">2843</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Spanish-AnCora-dev">2099</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Swedish-dev">286</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Swedish_Sign_Language-dev">14</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Upper_Sorbian-dev">147</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Urdu-dev">293</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Vietnamese-dev">85</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">26 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">2305 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">86 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">255 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">2254 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">333 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">27 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">1583 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">609 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">261 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">1282 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">206 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">125 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">52 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">895 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">1305 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">1217 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">978 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">439 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">295 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">2843 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">2099 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">286 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">147 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">293 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">85 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3C%21nummod%26%3C%21nmod%26%3C%21compound%29+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Marked as nummod but not NUM

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> If a word is marked as a numeric modifier, it should be marked as a numeral (POS).

Search expression: `!NUM <nummod _`

<a href="http://universaldependencies.org/docs/u/dep/nummod.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>DET</th><th>NOUN</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SYM</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Afrikaans-dev">52</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Afrikaans-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Afrikaans-dev">211</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Afrikaans-dev">45</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Belarusian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Catalan-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Catalan-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Catalan-dev">1</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Chinese-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Chinese-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Chinese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Chinese-dev">5</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Indonesian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Indonesian-dev">49</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Indonesian-dev">28</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Indonesian-dev">89</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Indonesian-dev">38</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Kazakh-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Kazakh-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Korean-dev">29</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Romanian-dev">30</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Romanian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Russian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Russian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Russian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Serbian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Serbian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Serbian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Spanish-dev">895</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Spanish-dev">195</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Spanish-dev">117</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Spanish-dev">23</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Spanish-AnCora-dev">1</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Urdu-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cnummod+_&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Cnummod+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">311 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">9 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">23 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">210 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">29 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">35 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">20 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">1232 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">12 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21NUM+%3Cnummod+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Marked as AUX but not aux or aux:pass

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> If a word is marked as the auxiliary POS, it should be marked as either aux or aux:pass dependency.

Search expression: `AUX (<!aux&<!aux:pass) _`

<a href="http://universaldependencies.org/docs/u/pos/AUX_.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>AUX</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Afrikaans-dev">776</a></td>
</tr>
<tr><td>UD_Bambara</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Bambara-dev">4</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Basque-dev">2485</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Belarusian-dev">22</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Bulgarian-dev">2577</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Catalan-dev">5076</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Chinese-dev">1805</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Coptic-dev">67</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Dutch-dev">3975</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Hungarian-dev">176</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Indonesian-dev">1056</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Japanese-dev">2409</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Kazakh-dev">190</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Portuguese-dev">2747</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Romanian-dev">2127</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Russian-dev">399</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Serbian-dev">1419</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Slovak-dev">1587</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Slovenian-dev">2826</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Spanish-dev">36</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Spanish-AnCora-dev">6606</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Swedish-dev">1614</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Upper_Sorbian-dev">240</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Urdu-dev">1243</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Vietnamese-dev">412</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">776 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">2485 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">22 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">2577 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">5076 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">1805 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">67 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">3975 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">176 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">1056 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">2409 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">190 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">2747 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">2127 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">399 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">1419 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">1587 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">2826 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">36 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">6606 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">1614 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">240 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">1243 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">412 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%28%3C%21aux%26%3C%21aux%3Apass%29+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Marked as aux or aux:pass but not AUX

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> If a word is marked as a (passive) auxiliary dependency, it should be marked as the auxiliary POS.

Search expression: `!AUX (<aux|<aux:pass) _`

<a href="http://universaldependencies.org/docs/u/dep/aux_.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>CCONJ</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SCONJ</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">39</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">30</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bambara</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">369</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">5</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">424</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">54</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Japanese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">823</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">55</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">143</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">1</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">8</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">32</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">9</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">24</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">1</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">500</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">60</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">39 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">41 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bambara</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bambara-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">387 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">25 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">17 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">424 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">92 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">878 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">6 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">152 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">52 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">25 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">36 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">588 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%21AUX+%28%3Caux%7C%3Caux%3Apass%29+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Marked as cc but not CCONJ, SYM or ADV

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> The relation cc is for coordinating conjunctions, hence the most expected POS tag is CCONJ. Symbols such as + may occasionally replace conjunctions, and in some languages some adverbs may take this syntactic function too. However, most other tags are suspicious at least.

Search expression: `(!CCONJ&!SYM&!ADV) <cc _`

<a href="http://universaldependencies.org/docs/u/dep/cc.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
Hits table not produced since the query does not start with the simple token spec '_'. Please add 'expr-pos' to the test which starts with '_' that will be substituted for the various POS in the links
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">54 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">4875 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">48 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">410 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">5 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">103 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">143 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">9 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Japanese</span>
<span class="widespan">632 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Japanese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">18 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">28 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">51 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">135 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">140 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">53 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">266 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">697 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">95 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">485 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=%28%21CCONJ%26%21SYM%26%21ADV%29+%3Ccc+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Cc is not leaf

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Coordinating conjunction should be attached to the first conjunct and it should not have its own dependents.

Search expression: `_ < (_ <cc _)`

<a href="http://universaldependencies.org/docs/u/dep/cc.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>DET</th><th>INTJ</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SCONJ</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">43</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">166</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">31</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">43</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">69</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">35</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">51</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">3</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">48</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">628</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">27</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">277</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">130</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">41</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">554</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">41</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">21</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">73</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">151</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">26</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">188</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">36</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">3</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">5</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">45</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">92</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">100</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">29</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">102</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">81</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">19</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">21</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">149</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">142</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">205</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">54</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">2</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">35</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">67</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">31</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">394</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">30</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">37</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">167</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">180</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">28</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">5</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">46 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">8 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">483 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">22 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">695 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">1555 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">56 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">64 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">11 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">184 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">153 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">144 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">91 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">7 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">59 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">623 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">1068 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">40 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">14 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">32 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Ccc+_%29&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


# Parts of speech of expl

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> The parts of speech of words marked as being expletive dependencies.

Search expression: `_ <expl _`

<a href="http://universaldependencies.org/u/dep/expl.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADP</th><th>ADV</th><th>NOUN</th><th>PRON</th><th>VERB</th> </tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Bulgarian-dev">3380</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Dutch-dev">122</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Dutch-dev">291</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Portuguese-dev">952</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Romanian-dev">540</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Romanian-dev">1</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Slovenian-dev">2298</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Cexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Cexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Cexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Cexpl+_&db=UD_Swedish-dev">493</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Cexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">3380 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">413 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">952 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">543 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">2298 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">493 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Cexpl+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
</div>


# Dependents of expl

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> The dependents of a word marked as being an expletive dependency. This should be empty.

Search expression: `_ < (_ <expl _)`

<a href="http://universaldependencies.org/u/dep/expl.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADP</th><th>ADV</th><th>CCONJ</th><th>DET</th><th>PUNCT</th> </tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">1</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">3</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">1</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">4 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Cexpl+_%29&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">3 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Cexpl+_%29&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">2 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Cexpl+_%29&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">15 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3C+%28_+%3Cexpl+_%29&db=UD_Romanian-dev">Go to search</a><p/>
</div>
</div>


# Heads of expl

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Parts of speech of words which have an expletive dependency.

Search expression: `_ >expl _`

<a href="http://universaldependencies.org/u/dep/expl.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>DET</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>VERB</th> </tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Bulgarian-dev">61</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Bulgarian-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Bulgarian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Bulgarian-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Bulgarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Bulgarian-dev">3272</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Dutch-dev">155</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Dutch-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Dutch-dev">21</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Dutch-dev">34</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Dutch-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Dutch-dev">196</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Portuguese-dev">949</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Romanian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Romanian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Romanian-dev">528</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Slovenian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Slovenian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Slovenian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Slovenian-dev">2292</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Eexpl+_&db=UD_Swedish-dev">121</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Eexpl+_&db=UD_Swedish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Eexpl+_&db=UD_Swedish-dev">20</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Eexpl+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Eexpl+_&db=UD_Swedish-dev">351</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">3367 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">413 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">952 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">540 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">2298 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">493 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Eexpl+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
</div>


# Heads of xcomp

<b>DEBUGGING TEST. NONZERO HITS DOES NOT MEAN THE DATA IS INVALID.</b> Parts of speech of words which have an open clausal complement dependency.

Search expression: `_ >xcomp _`

<a href="http://universaldependencies.org/u/dep/xcomp.html">Link to documentation</a>

<div id="accordion" class="jquery-ui-accordion">
<div>
<span class="doublewidespan" style="padding-left:3em">Hit overview</span>
<span class="widespan"> </span>
</div>
<div>
<table>
<tr><th/> <th>ADJ</th><th>ADP</th><th>ADV</th><th>AUX</th><th>CCONJ</th><th>DET</th><th>INTJ</th><th>NOUN</th><th>NUM</th><th>PART</th><th>PRON</th><th>PROPN</th><th>PUNCT</th><th>SCONJ</th><th>SYM</th><th>VERB</th><th>X</th> </tr>
<tr><td>UD_Afrikaans</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Afrikaans-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Afrikaans-dev">186</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Afrikaans-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Afrikaans-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Afrikaans-dev">85</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Afrikaans-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Ancient_Greek</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Ancient_Greek-dev">122</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Ancient_Greek-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Ancient_Greek-dev">676</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Ancient_Greek-dev">568</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Ancient_Greek-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Ancient_Greek-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Ancient_Greek-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Ancient_Greek-dev">4092</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Ancient_Greek-dev">1</a></td>
</tr>
<tr><td>UD_Basque</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Basque-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Basque-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Basque-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Basque-dev">55</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Basque-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Basque-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Basque-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Basque-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Basque-dev">1287</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Basque-dev">4</a></td>
</tr>
<tr><td>UD_Belarusian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Belarusian-dev">15</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Belarusian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Belarusian-dev">16</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Belarusian-dev">77</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Belarusian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Bulgarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Bulgarian-dev">733</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Bulgarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Catalan</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Catalan-dev">132</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Catalan-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Catalan-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Catalan-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Catalan-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Catalan-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Catalan-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Catalan-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Catalan-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Catalan-dev">2270</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Catalan-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Chinese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Chinese-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Chinese-dev">22</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Chinese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Chinese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Chinese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Chinese-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Chinese-dev">1653</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Chinese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Coptic</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Coptic-dev">25</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Coptic-dev">11</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Coptic-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Coptic-dev">84</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Coptic-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Dutch</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Dutch-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Dutch-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Dutch-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Dutch-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Dutch-dev">1342</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Dutch-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Hungarian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Hungarian-dev">34</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Hungarian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Hungarian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Hungarian-dev">268</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Hungarian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Indonesian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Indonesian-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Indonesian-dev">38</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Indonesian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Indonesian-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Indonesian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Indonesian-dev">1251</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Indonesian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Kazakh</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Kazakh-dev">17</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Kazakh-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Korean</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Korean-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Korean-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Latin</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Latin-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Latin-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Latin-dev">58</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Latin-dev">50</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Latin-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Latin-dev">600</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Latin-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Portuguese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Portuguese-dev">52</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Portuguese-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Portuguese-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Portuguese-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Portuguese-dev">40</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Portuguese-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Portuguese-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Portuguese-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Portuguese-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Portuguese-dev">1744</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Portuguese-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Romanian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Romanian-dev">63</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Romanian-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Romanian-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Romanian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Romanian-dev">1104</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Romanian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Russian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Russian-dev">75</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Russian-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Russian-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Russian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Russian-dev">626</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Russian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Serbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Serbian-dev">37</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Serbian-dev">13</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Serbian-dev">23</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Serbian-dev">14</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Serbian-dev">878</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Serbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovak</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Slovak-dev">31</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Slovak-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Slovak-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Slovak-dev">70</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Slovak-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Slovak-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Slovak-dev">34</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Slovak-dev">1041</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Slovak-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Slovenian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Slovenian-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Slovenian-dev">1189</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Slovenian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Spanish-dev">4</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Spanish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Spanish-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Spanish-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Spanish-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Spanish-dev">1393</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Spanish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Spanish-AnCora</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Spanish-AnCora-dev">149</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Spanish-AnCora-dev">9</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Spanish-AnCora-dev">8</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Spanish-AnCora-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Spanish-AnCora-dev">7</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Spanish-AnCora-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Spanish-AnCora-dev">5</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Spanish-AnCora-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Spanish-AnCora-dev">2394</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Spanish-AnCora-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Swedish-dev">12</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Swedish-dev">1</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Swedish-dev">10</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Swedish-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Swedish-dev">1029</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Swedish-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Swedish_Sign_Language</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">1</a></td>
</tr>
<tr><td>UD_Upper_Sorbian</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Upper_Sorbian-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Upper_Sorbian-dev">6</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Upper_Sorbian-dev">86</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Upper_Sorbian-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Urdu</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Urdu-dev">3</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Urdu-dev">448</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Urdu-dev">&nbsp;</a></td>
</tr>
<tr><td>UD_Vietnamese</td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADJ+%3Excomp+_&db=UD_Vietnamese-dev">248</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADP+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=ADV+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=AUX+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=CCONJ+%3Excomp+_&db=UD_Vietnamese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=DET+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=INTJ+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NOUN+%3Excomp+_&db=UD_Vietnamese-dev">1490</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=NUM+%3Excomp+_&db=UD_Vietnamese-dev">2</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PART+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PRON+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PROPN+%3Excomp+_&db=UD_Vietnamese-dev">18</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=PUNCT+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SCONJ+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=SYM+%3Excomp+_&db=UD_Vietnamese-dev">&nbsp;</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=VERB+%3Excomp+_&db=UD_Vietnamese-dev">1583</a></td>
<td><a href="http://bionlp-www.utu.fi/dep_search/query?search=X+%3Excomp+_&db=UD_Vietnamese-dev">2</a></td>
</tr>
</table>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Afrikaans</span>
<span class="widespan">299 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Afrikaans-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Ancient_Greek</span>
<span class="widespan">5470 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Ancient_Greek-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Basque</span>
<span class="widespan">1385 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Basque-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Belarusian</span>
<span class="widespan">109 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Belarusian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Bulgarian</span>
<span class="widespan">733 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Bulgarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Catalan</span>
<span class="widespan">2440 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Catalan-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Chinese</span>
<span class="widespan">1716 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Chinese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Coptic</span>
<span class="widespan">121 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Coptic-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Dutch</span>
<span class="widespan">1382 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Dutch-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Hungarian</span>
<span class="widespan">311 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Hungarian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Indonesian</span>
<span class="widespan">1321 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Indonesian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Kazakh</span>
<span class="widespan">17 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Kazakh-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Korean</span>
<span class="widespan">1 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Korean-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Latin</span>
<span class="widespan">720 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Latin-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Portuguese</span>
<span class="widespan">1878 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Portuguese-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Romanian</span>
<span class="widespan">1179 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Romanian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Russian</span>
<span class="widespan">715 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Russian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Serbian</span>
<span class="widespan">965 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Serbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovak</span>
<span class="widespan">1206 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Slovak-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Slovenian</span>
<span class="widespan">1197 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Slovenian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish</span>
<span class="widespan">1420 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Spanish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Spanish-AnCora</span>
<span class="widespan">2578 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Spanish-AnCora-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish</span>
<span class="widespan">1055 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Swedish-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Swedish_Sign_Language</span>
<span class="widespan">10 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Swedish_Sign_Language-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Upper_Sorbian</span>
<span class="widespan">94 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Upper_Sorbian-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Urdu</span>
<span class="widespan">451 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Urdu-dev">Go to search</a><p/>
</div>
<div>
<span class="doublewidespan" style="padding-left:3em">UD_Vietnamese</span>
<span class="widespan">3345 hits</span>
</div>
<div>
<a href="http://bionlp-www.utu.fi/dep_search/query?search=_+%3Excomp+_&db=UD_Vietnamese-dev">Go to search</a><p/>
</div>
</div>


