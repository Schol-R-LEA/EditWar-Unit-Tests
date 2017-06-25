# EdMark Reference Suite 
'''EdMark''' is a suite of tests for comparing the performance, costs, and benefits for the editing models used
by various editing tools, especially text editors. This reference suite is intended to provide a set of tests 
for directly testing the methods by which an editor manipulates the material it operates on; it is not meant to 
serve as a comparison between complete, operational text editors or word processors. The goal is to demonstrate
the efficacy, advantages, and disadvantages of different approaches to editing data, to allow developers of new
tools and utilities to make an informed judgement about design alternatives.

While to focus of the benchmarks is on editing of ASCII and Unicode text, independent of face or size and with
no inline or out-of-band markup, it is possible that it will be extended to cover various other kinds of
editing tools such as word processors, GUI textbox controls, outline editors, and even non-text editing
such as used by photoeditors or database engines.

However, at this time the suite does '''not''' cover either text rendering or user interface operations; it
is solely for testing the behavior of the editing operations themselves.
