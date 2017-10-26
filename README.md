# personalysis
Analyzing personality test results and identifying key traits

This is a technique I'm experimenting with. Let's say you have a bunch of psychometric data, and you want to figure out which questions correlate together. The goal is to combine them in order to create new factors. What if we tried doing this manually, and let the *data* tell us how many factors we need?

The notebook contains one method for doing this: iterate through the questions in order of how controversial they are, and cluster the questions that correlate together.

I'm currently experimenting with another method in which I try to find factors that are orthogonal to the ones we've already discovered. I'll update the notebook when I find a technique that works!
