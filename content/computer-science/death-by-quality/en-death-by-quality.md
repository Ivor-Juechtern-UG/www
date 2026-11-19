---
title: Death by Quality
draft: true
authors: 
image: images/mutation-tests.png
explanation: A mutation test run on seven cores at once; the number in brackets is the core. Each line is one mutant, a small change planted in the code, such as &laquo; &lt; &raquo; turned into &laquo; &lt;= &raquo;, with its number among the mutants of its file. &laquo; Killed &raquo;: a test noticed the change. &laquo; Survived &raquo;: no test did. &laquo; No code change &raquo;: the mutant is the same program as the original.
---

In 1971, Richard Lipton invented mutation tests.

He was a student then. The idea is simple: plant a small fault in the code, run the tests, and see whether they notice. A test that notices kills the mutant. A mutant no test notices survives, and shows where the tests are blind.

In 1978 Richard DeMillo, Richard Lipton and Frederick Sayward published it: __Hints on Test Data Selection: Help for the Practicing Programmer__, in IEEE Computer.

For fifty years it stayed mostly an idea. Every mutant needs the whole suite of tests to run again, and every survivor asks for a new test that someone has to write.

# Audience

To come.

# The Vocabulary of Death

To come: mutants are killed, they survive; the language of the method is the language of death.

# Ahead of Its Time

To come: the technology to carry the idea was missing. Now droids write the tests, and the cores that sit idle overnight run them.

# Death by Quality

To come.
