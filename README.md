# Personality from scratch
Analyzing personality test results and identifying key traits... from scratch!

This is a technique I'm experimenting with. Let's say you have a bunch of psychometric data, and you want to figure out which questions correlate together. The goal is to combine them in order to create new factors. What if we tried doing this manually, and let the *data* tell us how many factors we need?

The notebook contains two methods for doing this:

The first iterate through the questions in order of how controversial they are, and clusters the questions that correlate together.

The second method, which I prefer, sequentially finds traits that correlate **least** with the traits we've already discovered.
