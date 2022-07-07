# Russsian-English bilingual phrase dictionary
This page contains the **automatically constructed** Russian-English bilingual phrase dictionary. It was built based on the Russian-English sub-corpus of [CCMatrix dataset (v1)](https://opus.nlpl.eu/CCMatrix.php) using GIZA++ statistical tool. The source of Russian phrases is the [dictionary of n-gram lexical units](https://ruscorpora.ru/new/obgrams.html) from Russian National Corpus.

_This dictionary should be used only as a source of translation options, which should be checked elsewhere if a person is unsure, keeping in mind the automatic nature of this language resource. It also can be used by those who work on creating language learning tools and writing assistants as a raw resource for further processing._ 

The constructed dictionary consists of 5 sections, each of which contains phrases of a certain type:
1. prepositions (обороты в функции предлога), n=187, e.g.:
- согласно с ‘in accordance with’,
- во имя ‘in the name of’;

2. adverbs and predicatives (наречные и предикативные обороты), n=1589, e.g.:
- в итоге ‘ultimately’,
- в двух словах ‘in a nutshell’;

3. conjunctions and connective words (обороты в функции союза и союзного слова), n=53, e.g.:
- а именно ‘namely’,
- если бы ‘if only’;

4. particles (обороты в функции частиц), n=16, e.g.:
- едва не ‘nearly’,
- как раз ‘exactly’; 

5. comment clauses (вводные обороты), n=163, e.g.:
- без сомнения ‘undoubtedly’,
- грубо говоря ‘roughly speaking’. 


The dictionary comes as tab-separated `.txt` files where every line contains a Russian phrase and one of its English translations. For every Russian phrase there may be up to 10 translations, but on average there are 1-2. If there are several translations for a phrase, they appear in consecutive lines.

The link to the paper with the detailed explanation of how this dictionary was constructed is to be provided.
