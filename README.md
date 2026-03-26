Glad
=====
ImGicc Global Language Data, common data of multiple languages for AI/ML.

Files
=====
There's only 1 file named `tokens.mjs` for syllables of all languages and symbols.
This file is **append-only** and the indexes of tokens always stay the same
for added tokens.

Tokens will be added by batch (large batch of tokens from texts submitted by users)
to ensure a bit of the relation between related tokens. The first 3 batches
are: English Dictionary, Italian Dictionary, Vietnamese Dictionary.

More Tokens
===========
Please go [Issues](https://github.com/imgicc/glad/issues) tab to submit text files 
to have the tokens added.

Notes
=====
Note that the indexes of tokens start from zero, but actually start from 256
to reserve the index 0..255 for bytes of unknown tokens.

Licence
=======
GNU GPL v3
