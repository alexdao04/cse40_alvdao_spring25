# CSE 40 Notes, April 3, 2025
Name: Alexander Dao

- Deductive Reasoning
    - General -> Specific
        - Starts with the assertion of a general rule
        - Arrives to a guaranteed specific conclusion.

    - In deductive reasoning, if the original assertions are true, 
    the conclusion must also be true.
        - "If all birds can fly..."
        - "... and Tweety is a bird..."
        - "... then Tweety can fly"

    - "Modus ponens": deductive rule. If X -> Y, and X is true, then Y is true.
        - to be honest i learned this shit in cse16, but taking it concurrently with this class might be a good thing now that i think about it.

    - Deductive Reasoning is NOT Machine Learning.

- Inductive Reasoning
    - Begins with observations that are specific and limited in scope.
    Proceeds to a generalized conclusion that's likely, but not certain,
    given accumulated evidence.
        - Most commonly seen in scientific reasoning (e.g. hypotheses).

    - X was true once (X1), X was true again (X2), X was true again... (X3)
    - Generalized rule: X is always true (for all n, Xn)
    - X will be true in the future (for some future time t, Xt)
    - How many observations? What features matter? What generalizations are valid?

    - Inductive Reasoning is only "probable".
        - Conclusions reached by this method are NOT logical necessities; no amount of
        inductive evidence can guarantee our conclusion.

    - "Cogent" Inductive Reasoning:
        - Since inductive conclusions aren't "sound" in the sense of deductive reasoning
        (they're not necessarily for SURE the truth)
            - We call this "cogent' meaning the evidence is relevant, complete, and convincing
            enough that our conclusion is likely true.

- Abductive Reasoning
    - 