# pycat

This is an attempt to re-implement ye old favorite [`cat`](https://man7.org/linux/man-pages/man1/cat.1.html) in an effort to learn a thing or three.

## Setup

This project uses [`poetry`](https://python-poetry.org/) to manage itself.

## Notes

- this is a _really_ naive implementation, and I mean that all of this is sitting in a big for-loop in one function. my original thought was to make one function for each flag, but then how would I deal with combinations of flags? maybe I need to build a function for each flag that returns a list of strings, and pass that to a function that prints to stdout? then it feels like an order-of-operations kind-of-problem, which could be more approachable?
