Disclaimer - this is just a collection of random thoughts for me as I'm designing this project. This is meant for me and not really for end users.

# Language thoughts

**Use my own pseudo-code** / language to have control over what we can do at any moment. Change it constantly to fit the module
 - has the side effect of giving me a lot of language creation experience which sounds like fun

**Maybe make an interpreter for it?** It would have to be different for each language modification (but that's ok).
 - my first thought is using python for the string handling
 - js could run in the browser
 - java would give me a better oop solution (modular interpreter)
 - racket might be built for this perfectly tho

Could also compile it to some other language (js so it can run the browser)
 - issue : the source language would have to be a subset of the target langauge
 - issue : the target language could influence decisions made in the source language

Make it an extension of an existing language
 - issue : it can make using the original language hard (build on top of python, now using python in the future is hard because "thing X doesn't exist anymore")

