# Simply-Functional
A bridge between programing languages

> AI Policy [Here](/ai-policy)

## What is Simply Functional (Or SFunc)?
**SFunc** is a bridge between programing languages, instead of building a internal API to connect Rust and Python, JS and Go, or any other languages you can directly import SFunc allowing you to use functions from one file in one language, and use them in another file with another language.

## Why SFunc and not other tools?
SFunc is the **only** all in one tool to offer excellent developer expirence across all programing languages, this prevents having multiple large dependances, and messy deployment with fast easy solutions for multi-language repos.

## Q&A
### How do you handle type systems?
Most languages support all types this is as simple as moving them over to the format the language wants, it does increase memory by about double but for easy multilanguage support its worth it.

### How do you handle compiled vs interpreted?
We compile any compiled languages first before running the interpreted ones, this ensures fast calls of the functions when they are needed at the cost of slightly slower build times.

### How long do you expect this to take to build?
Version 0.1.0 should be available in 30-40 hours of building our team is already working hard!

## Road Map
- Add Python to JavaScript
- Add Rust Support
- Add Go Support
- More languages