---
layout: post
date: 2015-10-01
title: ADAPT Centre Project Ideas

---

#General Introduction

The [ADAPT Centre](http://www.adaptcentre.ie) is an
[SFI](http://www.sfi.ie)-Funded Research Centre focused on developing the
future of Digital Content. _Digital Content_ in this case means anything
containing language or images, which can be stored and retrieved with a
computer. Digital Content represents more than 80% of the information out
there, far more than structured Data.

## Research Themes

ADAPT at DCU has research themes including personalisation, machine
translation, information retrieval, text analytics, natural language processing
and web engineering. Underpinning these approaches is an extremely strong focus
on cutting-edge user experience design, machine learning (including deep
learning) and industrially-relevant research. ADAPT has numerous industrial
partners, including [Intel](http://www.intel.com),
[Microsoft](http://www.microsoft.com), [Huawei](http://www.huawei.cn),
[WeLocalize](http://www.welocalize.com), and others.

## Information for Students

For __DCU Students__, ADAPT researchers are interested in pursuing high-quality
projects in the different research areas, and perhaps with the involvement of
industry partners. Projects with a research focus, or an industrial application
are especially welcome.

Key ADAPT Researchers at DCU offering projects include:

* Prof. Andy Way
* Prof. Qun Liu
* Dr. Gareth Jones
* Dr. Jennifer Foster
* [Dr. Alexander O'Connor](http://www.oconnoat.com/projects/)
* Dr. Xiaofeng Wu

## Specific Projects

### Real-time Online Incrementally Retrained SMT

In the application of statistical machine translation (SMT) for post-editing (PE),
we always face the issue of adapting SMT system to user’s data/domain in real
time to provide high-quality translation results , which requies that we must
learn new knowledge from the newly post-edited data to update SMT models on the fly.

#### Tasks in the project

1. Learn how to install and use open source SMT toolkits, including Moses and cdec.
2. Be able to build up a batch-mode incremental retraining SMT system using Moses and cdec respectively.
3. Develop online incremental retraining modules: parameter tuning, language model and translation model etc.

#### Requirements

1. Be familiar with programming languages, such as java, c/c++, Python or Perl;
2. Has the basic knowledge of NLP or SMTProject 1: Real-time Online Incrementally Retrained

### High-Concurrency Web Service-based SMT System

In the application of statistical machine translation (SMT), it is generally deployed as a Web
server which can be remotely accessed by different users. However, due to the limitation of
hardware resources, when the SMT server faces high concurrency requests, it will significantly
delays the processing of requests. In this project, we will develop a reasonable and feasible
strategy to manage the high concurrency request and return results in an acceptable time.

#### Tasks in the project

1. Learn how to install and use open source toolkit Moses.
2. Build up an SMT server using Moses and simulate the high concurrency access to the server.
3. Design and develop a strategy which can reasonable handle the high concurrency request to SMT server.

#### Requirements

1. Be familiar with Java and socket programming.
2. Basic knowledge of NLP or SMT

### Question Answering for Database (for Master students)

Given a database which contains at least three tables, please build a system
which can answer natural language questions for the database.  For example,
there is a database with three table which contain information of students,
modules and the module selection of each students.  The system should be able
answer questions like: "How many students select modules which is taught by
John Smith?", "What is the average marks of all modules for 4th year female
students?"

#### Contact

Prof. Qun Liu

### Automatic Transliteration (for 3rd/4th year undergraduate students)

Please implement a automatic transliteration system which can transliterate an
proper name from one language to another language which use different writing
systems, for example, from Chinese or Arabic to English.  First, you should collect
parallel data for training.  Then you should training a system to implement the
transliteration.  Finally you should evalute the precision of the transliteration.

#### Contact

Prof. Qun Liu

### Sentence recovering from a bag of word (for 3rd/4th year undergraduate students)

Given a bag of words (a word can occur more than once in the bag), please find
the most possible sentence which is exactly composed by the words in the bag.
Every word in the bag should be used exactly the same times as in the bag, and
no additional word can be used.

#### Contact

Prof. Qun Liu


### Paraphrase engine for ProphetMT.

ProphetMT provides an accessible user interface that allows a user write 
in a subset of a natural language that computers can understand. Therefore 
the machine translation and other computer-related processing is much more
reliable than the current state-of-the-art methods.

A working demonstration of ProphetMT exists and works on Symantec
technology document writing.

#### Paraphrase Engine

Although ProphetMT encourages user to use the words or phrases within the MT
model  (i.e. machine can "understand"), there is still a chance that users input
some new words or write something in his own style. Therefore, a paraphrase
engine, which takes the user's input and find the closest matching phrases in the
MT model is very important.

#### Challenges & benefits

The student is going to have hands on experience of Machine Learning & NLP &
MT & Client/Server programming

### Contact

Dr. Xiaofeng Wu

### Tweet translation model for iHearU.

IHearU is a mobile app that allows reliable hands-free eyes-free communication
with  a user’s social networks. iHearU uses a novel mode of interaction and
content delivery  for social media. iHearU also provides Domain-adapted
machine translation(currently Spanish to English), which translates foreign
language social media text into the user’s own language. IHearU has a working
demo on twitter.

This project aims at building a machine translation model for anther language
pair (for example, French to English)

The main work includes: 

1. to use NLP tools to collect parallel corpus of tweets or alike social media. 
2. to use NLP tools to collect monolingual corpus for language model.
3. to build robust domain-adapted Moses machine translation engine
4. deploy the engine on server

#### Challenges & benefits:

The student is going to have hands on experience with a lot of famous NLP tools
& Moses & Domain-Adapted Machine Translation Method

Note: The students are all welcome to see the demos iHearU and ProphetMT.

#### Contact

Dr. Xiaofeng Wu



## Contact

If you would like to discuss a project idea of your own, or one of the proposed
projects, please email [Alexander O'Connor](Alexander.OConnor@dcu.ie) or [Andy
Way](Andy.Way@dcu.ie) with a brief outline.



