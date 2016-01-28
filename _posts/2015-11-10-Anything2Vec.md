---
layout: post-no-feature
title: Anything2Vec
description: "An in-depth look into the embedding world and how word2vec is really fits the NN mold"
categories: articles
comments: true
published: true
date: 2015-11-10
---

This might be old news to you, but if you're considering the use of word embeddings, our suggestion: just take the plunge. We've read a "few" studies documenting their effectiveness, not the least of which is our personal favorite:

> This paper is summarized best by its own statement, which should win it the award for most honest paper ever: ...we set out to conduct this study because we were annoyed by the triumphalist overtones often surrounding [neural network embeddings], despite the almost complete lack of a proper comparison.... Our secret wish was to discover that it is all hype... Instead, we found that the [embeddings] are so good that, while the triumphalist overtones still sound excessive, there are very good reasons to switch to the new architecture.

Baroni, Dinu, & Kruszewski are a bit dramatic, but they get the point across. You may not be able to explain why (though we'll try, here), but embeddings sure done work good. And as the most popular word embedding algorithm, not many techniques have caught fire as much as Tomas Mikolov's word2vec algorithm.

In 2013, word2vec made waves in the neural network world. The code was readable and really fast (multi-threaded C code), helping it achieve wide adoption. Since then, Google archived the code (though it's still available), and Mikolov changed companies. Still, that didn't stop the momentum, and there's been a glut of implementations on platforms and software packages like Python, Scala (and ML-Lib in Spark), DL4J, gensim, and maybe a zillion more, to make it fit into the everyday man's NLP toolbox.

........


For the full blog, go to: https://www.lab41.org/anything2vec/
