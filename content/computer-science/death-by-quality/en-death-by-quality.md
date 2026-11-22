---
title: Death by Quality
authors: 
image: images/mutation-tests.png
explanation: A mutation test run on seven cores at once; the number in brackets is the core. Each line is one mutant, a small change planted in the code, such as &laquo; &lt; &raquo; turned into &laquo; &lt;= &raquo;, with its number among the mutants of its file. &laquo; Killed &raquo;: a test noticed the change. &laquo; Survived &raquo;: no test did.
---

In 1971, Richard Lipton invented mutation tests.

He was a student then. The idea is simple: plant a small fault in the code, run the tests, and see whether they notice. A test that notices kills the mutant. A mutant no test notices survives, and shows where the tests are blind.

In 1978 Richard DeMillo, Richard Lipton and Frederick Sayward published it: __Hints on Test Data Selection: Help for the Practicing Programmer__, in IEEE Computer.

For fifty years it stayed mostly an idea. Every mutant needs the whole suite of tests to run again, and every survivor asks for a new test that someone has to write.

# Audience

This article is written for developers who now let droids write their tests, and for those who decide how much testing is enough.

# The Vocabulary of Death

The method speaks the language of life and death. A mutant is born from one small change: &laquo; &lt; &raquo; becomes &laquo; &lt;= &raquo;, &laquo; true &raquo; becomes &laquo; false &raquo;, a 1 becomes a 2. The tests run. Either they notice, and the mutant is __killed__, or nobody notices, and it __survives__.

Some mutants can never die. The run marks them &laquo; no code change &raquo;: the change made the same program, and there is nothing for a test to notice. They are called equivalent mutants. They are immortal, and they cost as much time as the others.

Each survivor is a question. In the image: line 52, &laquo; &lt; &raquo; turned into &laquo; &lt;= &raquo;, survived. Somewhere a limit can sit one step further out, and no test minds.

# Ahead of Its Time

Mutation tests are an idea that came before the technology to carry it. The biologist Stuart Kauffman called the next reachable step the adjacent possible: an idea becomes real once the steps next to it exist.

For mutation tests, two steps were missing. Running: one file in the image has 398 mutants, and each needs the tests to run again. Writing: each survivor asks for a new test, and someone has to write it.

Both steps are here now. The cores that sit idle overnight, at home or in the office, run the tests. Droids write the new ones. Approaches to quality that waited fifty years have become cheap.

# Death by Quality

Cheap is not free. A droid will write a test for every survivor, tirelessly, like the broom of the Sorcerer's Apprentice carrying water. The tests grow faster than the code.

Three deaths follow:

1. __Death by reading.__ Writing tests costs nothing now; reading them still costs a person. Every test is something someone has to understand before they change the code.
2. __Death by freezing.__ A test written only to kill a mutant often holds the code exactly as it is. The next change, however good, kills a dozen tests, and nobody dares to make it.
3. __Death by immortals.__ Equivalent mutants cannot be killed. Chasing them is work without end.

The answer is not fewer tests, but a decision about what quality is for. Kill the mutants where an error would hurt: money, safety, the edges of a limit. Let others survive on purpose, and write down why. A survivor is a question, not an order.

# Sources

* R. A. DeMillo, R. J. Lipton, F. G. Sayward, __Hints on Test Data Selection: Help for the Practicing Programmer__, IEEE Computer 11(4), 1978.
* S. Kauffman, the adjacent possible, as popularised by S. Johnson, __Where Good Ideas Come From__, 2010.
