---
layout: post
date: 2015-09-16
title: Project Ideas

---

# General Themes

I have general interest in machine learning, especially [deep learning for natual language processing](http://www.socher.org/index.php/DeepLearningTutorial/DeepLearningTutorial). I am also interested in personalisation and web technologies, and the link with machine learning. I am open to suggested projects in these fields, drop me an [email](malito:Alexander.OConnor@scss.tcd.ie) to arrange a discussion.


# Specific Projects

These would probably most likely suit CA or MCM students with an interest in machine learning, language technology or the World Wide Web.

## Entity Linking in Literary Fiction

Named Entity Recognition and Disambiguation is a natural language processing task which concerns the recognition that certain words refer to _entities_ (People, places, times, events). Human language is highly referential and varied, and it can be difficult to decide precisely _which_ entity is being referred to.

A large amount of effective NLP is based on using journalistic, general content, where there is considerable [background knowledge](http://www.dlib.org/dlib/march06/crane/03crane.html). This works well where the data being examined is also in a modern language and refers to modern things. A key challenge is where the collection of data is '[idiosyncratic](http://dl.acm.org/citation.cfm?id=2568013)': different in structure, vocabulary or size. This project would look at training a system to recognise entities such as characters, places and events in narrative text.

This project would look at disambiguating and linking character references in novels from the Gutenberg collection.

## Semantic Textual Similarity

This task is based on the [Semeval-2015 Task 2](http://alt.qcri.org/semeval2015/task2/) and is concerned with the question:
     "Given two sentences, do they say the same thing, even if they use different words?", or "Are the different sentences in this pair equivalent?"

The task is interesting because some paraphrasing is extremely difficult to recognise, and creating a system that can find paraphrases without significant manual intervention would be of great value.

## Experiments in Word Embeddings

[Word Embeddings](http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/) refer to the notion that by transforming free text into high-dimentional vectors, hidden meaning can be found. The benefit of doing this appears to be that the resulting vectors can be used for a variety of applications. One which has caught the imagination of researchers is the ability to infer relationships for different words. For example, it has been shown that a system can be trained that can answer ``"Rome"`` to the Equation ``"France - Paris + Italy"``, or ``"Queen"`` to the Equation ``"King - Man + Woman"``.

This project would look to explore the different possible uses for Word Embeddings, and in particular how to improve their consistency and reliability on different-sized collections of documents.



