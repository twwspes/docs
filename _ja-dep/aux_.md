---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
redirect_from: "ja/dep/aux.html"
---

Auxiliary verbs and particles that attach to verbs.

~~~ sdparse
ご飯 を 食べ た 。 \n rice ACC eat PAST .
case(ご飯, を)
dobj(食べ, ご飯)
aux(食べ, た)
punct(食べ, 。)
~~~

~~~ sdparse
行き ます か 。 \n go POLITE QUESTION .
aux(行き, ます)
aux(行き, か)
punct(行き, 。)
~~~
