# Irish Word Frequency List

This is a list of approximately 6,500 Irish lemmas (= "words") ordered by frequency of use. It has been extracted from the Irish half of the [New Corpus for Ireland](http://corpas.focloir.ie/) and then cleaned up by cross-checking against a large-coverage lexicon (Kevin Scannell's [Líonra Séimeantach na Gaeilge](https://cadhan.com/lsg/)) and removing lemmas that don't occur in this lexicon. The result is a list which is "clean" in the sense that it doesn't contain any punctuation, personal names, English words or other noise.

## License

Available under the [Open Database License](http://opendatacommons.org/licenses/odbl/summary/).

## Format

This is a plain-text tab-delimited file encoded in UTF-8 with Windows-style line breaks.

- Column 1 is the lemma's rank: number 1 means the first most frequently used lemma, number 2 the second, and so on.
- Column 2 is the lemma itself.
- Column 3 is the lemma's corpus frequency: a number that says how many times it occurs in the entire corpus.
- Column 4 is the lemma's window size: it tells you that the lemma occurs on average once in this number of words.
