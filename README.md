# grok.poetry-import-clashes

Consider this dependancy graph.
    [carrot ver 0] -> [apple ver 0]
    [carrot ver 0] -> [banana ver 0] -> [apple ver 1]

Q1. Does [carrot ver 0] build?
Q2. If so, what versions of [apple] get called at runtime?
Q3. Does this warrant use of a monorepo?

We wish to grok this.
