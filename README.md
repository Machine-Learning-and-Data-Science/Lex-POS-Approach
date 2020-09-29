# Lex-POS-Approach
Lex-Pos sequence has the potential to imbibe the specific nature of the linguistic words (i.e. lexicals) and generic structural characteristics of a sentence via Part-Of-Speech (POS) tags, and so, can lead to a significant improvement in detecting grammar errors. A new vector representation technique, Word Embedding One hot Encoding (WEOE) is introduced to transform Lex-POS into mathematical values.

This project contains following files:

#1) Three datasets:

          a)  correct sentences (combined_tagged_lang_selected_entries.csv)
          b)  incorrect sentences with general errors  (combined_tagged_general_error_lang_selected_entries.csv)
          c)  incorrect sentences with tag-specific errors combined_tagged_specific_error_lang_selected_entries.csv)
            
 Each dataset has three columns
 
             First Column : Lexical Sequence
             Second Column: PosTag Sequence
             Third Column: Lex-POS Sequence

2) Three jupyter notebook files 

          a) lstm_linguist_embedding.ipynb (Lexical Sequence + Word Embedding)
          b) lstm_hot_coding.ipynb (PosTag Sequence + One Hot encoding)
          c) lstm_hotcode_embedding.ipynb (Lex-POS Sequence + WEOE embedding)

3) pos-tag.csv: This file contains vocabulary of POS-tags used in lstm_hot_coding.ipynb and lstm_hotcode_embedding.ipynb.


__________________________________________ ________________________________________
