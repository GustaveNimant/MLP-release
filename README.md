---
---
<meta charset=utf8/>

# Minimum Lovable Product (architecture documents)


### What do we want ?

 - set the tools to help large group to produce a single text or a reduced set (output)
   set of text is to be submitted to referendum
   that consider **all**  nodes' (individual) versions (inputs)
 - final version is obtained by applying a merge algorithm in a distributed manner.
 - requirements:
     each documents need to be equally reviewed
     every willing members need to participate _equally_ (sovereignty is not sharable)
     participation must be "de-indentified" (tokenisation)

 - one time delegation (voting token: avoid power, all token must be used)
 - several rounds for reduction of proposed texts

 - democracy processus of generalization of a politic proposition
   to reveal the generality (hard/soft consensus)

 - when deciding on future hypothesis are made, ... (if else)
 



### RELEASE 0.0:

1. [fairPad][1]: module saisie version (optionally collaborative)
   proposed texts are locally stored in each nodes and must be registered to be considered
   (need redundancy among registration servers)

2. [fairToken][2]: module fair distribution of token

3. [fairPublish][3]: module distribution of version (gossip ?)

   common knowledge of where to find texts (urn...) (common knowledge to be pushed)
   ex. /public/round-1/1-50/text45 (locally centralized: P2P pull)
   
4. [fairRank][4] module ranking & reduction texts (merge tools)

5. [fairMerge][5] interation until reduced set is equally contradictory (option).

6. [fairDecide][6] module vote to decide on final options


### naming convention

  [fairName](fairName.md)

### definitions ...

 for a glossary see also [here](glossary.md)
