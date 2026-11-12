# Analysis

## Layer 8, Head 11

The attention is limited to nouns related to verbs: 

    sentence 1: cat and climbs, tree and falls.
    sentence 2: Holmes and sat, cried

Example Sentences:

- The cat climbs fast [MASK] the big tree and falls.
- Holmes sat in front of [MASK] and cried.

## Layer 1, Head 10

The attention of all the words is concentrated on the MASK. 

Example Sentences:

- A man in the [MASK] walked slowly.
- The the [MASK] barked and ran away with the bone.

## Layer 1, Head 1

I tried some sentences in English and the same in French.
First observation, the French version contains many words broken in subtoken: 'grim' 'pe', 'gr' 'os', 'tom' 'be'. This makes the comparison more difficult. 
Generally, the matrices are very similar, however, there are some that look very different.

Example Sentences:

- The cat climbs fast [MASK] the big tree and falls.
- Le chat grimpe vite [MASK] le gros arbre et tombe.