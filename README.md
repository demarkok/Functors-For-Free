# Functors-For-Free
A research in type theory: application of the Free theorem for Functors.

The functors (e.g. in Haskell) have two laws: 
`fmap id = id` 
`fmap (f . g) = (fmap f) . (fmap g)`. 
We show that in some specific domain the second law is redundant and could be inferred from the first one.
See [FunctorsForFree.pdf](https://github.com/demarkok/Functors-For-Free/master/FunctorsForFree.pdf) (RUS).
