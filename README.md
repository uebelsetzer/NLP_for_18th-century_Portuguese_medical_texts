# NLP for 18th-century Portuguese medical texts
This is a repository for the paper:
Zilio, L., Lazzari R.R., Finatto, M.J.B. (2024) NLP for historical Portuguese: Analysing 18th-century medical texts. In _Proceedings of PROPOR 2024_.

## Repository content:
```
_TMX_: this folder contain original and normalised versions of the texts described in the paper in a TMX format (a type of XML format)
_aligned_: this folder contains the results of semi-automatic alignments between original and normalised versions of each file of the corpus
_parsed_: this folder contains the automatically parsed version of the files (parsing done with STANZA)
```
The file `aligned_parsed_modern_PT_NLTK_tokenizer_stanza.tsv` contains an automatic parsing (with STANZA) combined with the alginments for the whole corpus. The second column of the parsing is the semi-automatically aligned original spelling of the token.
