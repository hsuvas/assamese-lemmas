# ass-lemmas
This repo contains an implementation of GUI based Lemmatizer for Assamese Language. The approach is taken as Hybrid Lemmatizer that contains 3 things:
1. Trie Based approach  : a trie of the lemmas is created with a searching function that can search the trie for lemma of the Inflected words.
2. Rule base: A rule base to handle the verbs whose inflected forms starts witth different letter than the lemma (eg.: গৈছিলো: যা, উপজিব: ওপজ etc).
3. a stripping strategy: This is used to strip those inflected words that differ structurely.
The associated files are added with the code.

 for any problems regarding code: contact @ hsuvas@gmail.com
