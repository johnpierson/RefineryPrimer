# Evaluators

An evaluator \(also known as a discriminator\), is fed potential solutions from the generator and evaluates how good or bad these solutions are. Evaluators are a natural analogue of the objective and fitness functions outlined in [section 4-08](5-03_evaluators.md#what-do-you-mean-by-‘fitness’?). In a generative building design, an evaluator may be a function that describes the average amount of sunlight a façade will be exposed to over a year.

In design, evaluators must be specified mathematically, they must output a number that can be used to discriminate between solutions.
