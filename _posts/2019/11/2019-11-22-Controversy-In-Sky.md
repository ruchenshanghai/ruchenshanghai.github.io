---
layout: post
title: Controversy in sky
---

Discovering, Explaining and Summarizing Controversial Discussions in Community Q&A Sites \\
Controversial answers: wrong, less optimal, out-of-date, critique posts \\
Posts and official documents ➡️
1. controversial answers & critique posts
2. documents related controversies
3. summarize controversies warnings

<br />
![alt text]({{ site.baseurl }}/images/2019/11/ASE19-Controversy-Structure.png "image alt"){: .center-image }
<br />

1. Input documentation ➡️ software-specific tokenizer, Stanford CoreNLP,
2. Discover controversies: \\
Critique Posts: answers or comment. Identified by \\
a). critical indicators: judgment, sentiment, opinion; \\
b). similarity score with critique sentences by sentence matching.
Controversial Answers: Identified by, \\
a). critique comments identify the controversial answers; \\
b). critique answers refer to other controversial answers by metadata; \\
c). critique answers implicitly refer to other controversial answers by text-summary-and-matching (TextRank) to extract important sentences, sentence matching method to find similar answers, bipartite graph matching algorithm to determine the optimal sentences pairs, average sentence similarity to find the biggest controversial answer.
3. API-related controversies: explanatory API links/caveats, \\
a). Identify API-Related Controversial Posts: API token-name matching, API hyperlink mentioned; \\
b). Extract Explanatory API \\
Links, caveats (lexical gap between controversies and documents, weighted word-embedding based sentence matching method), API-caveat mining (explicit, restricted, general), pair post sentences and API-caveat sentences; \\
c). Weighted Word Embedding Based Sentence Matching, \\
Word embedding: from word to vector, Term-Frequency-Inverse-Document-Frequency (TF-IDF): from word to weight, combine weight and vector to get weighted word embedding vector of sentence level, cosine similarity,
4. Summarizing controversies,
Controversy summary: highlighted critique sentences, highlighted API-caveat explanations (appended to the below). \\
Four key steps: detect critique, identify controversial posts, identify API related controversies, extract explanation API caveats. Cohen's Kappa,

<br />
<br />
TBD: Controversy summary, word2vec, CBOW (Continuous Bag-Of-Words), Skip-Gram, Negative Sampling