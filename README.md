# Lex-POS-Approach
Lex-Pos sequence has the potential to imbibe the specific nature of the linguistic words (i.e. lexicals) and generic structural characteristics of a sentence via Part-Of-Speech (POS) tags, and so, can lead to a significant improvement in detecting grammar errors. A new vector representation technique, Word Embedding One hot Encoding (WEOE) is introduced to transform Lex-POS into mathematical values.

There are three datasets:
            correct sentences (combined_tagged_lang_selected_entries.csv)
            incorrect sentences with general errors  (combined_tagged_general_error_lang_selected_entries.csv)
            incorrect sentences with tag-specific errors combined_tagged_specific_error_lang_selected_entries.csv)
            
 Each dataset has three columns
             First Column : Lexical Sequence
             Second Column: PosTag Sequence
             Third Column: Lex-POS Sequence

There are three notebooks used to conduct experiments
lstm_linguist_embedding.ipynb (Lexical Sequence + Word Embedding)
lstm_hot_coding.ipynb (PosTag Sequence + One Hot encoding)
lstm_hotcode_embedding.ipynb (Lex-POS Sequence + WEOE embedding
