---
uid: ryanrhymes
date: 2016-10-10
enddate: 2016-10-16
week: 42
generator: furore
---

This week I have been working on the Plot module in Owl library by adding more basic plotting functions. Currently the Plot module supports many widely used plots. There are still many minor things in the module can be improved, but I will do that slowly in the future. I also wrote a tutorial on how to use the plot module and sent it to the ocamllabs mailing list.

Besides the Plot module, I am also focusing on the Stats module because GSL only provides very basic ones and there are many useful statistical functions are missing. I will implement most of them by myself in OCaml since I do not want to introduce too many dependency in the library. So far, I have implemented z-test, t-test, jb-test, chi2-test, and so on. Based on the feedback, it becomes clearer now that Owl will evolve into a numerical library for OCaml and Matrix, Maths, Stats, Regression, and Plot will be the core modules.

