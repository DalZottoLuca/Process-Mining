# Process-Mining
Process Mining Course - Data Science Master Degree - Unipd

In this project, we were asked to face a prediction
task starting from an event log, exploiting what we
have learnt during the lectures. In particular, a
certain emphasis will be given to the encoding phase,
exploring the contribution of time related features.
The dataset considered for this purpose is the
real-life event log used for the first Business Process
Intelligence Challenge, in 2011. It consists in 1140
cases, and each trace collects the different phases that
a patient of the Dutch Academic Hospital undergoes.
In the BPI scenario, great importance is given to the
encoding phase, in which all relevant information are
extracted from the event log and rewritten in a format
that allows further analysis, as well as the training of
machine learning algorithms. In this specific case, we
were asked to perform two encodings: one using only
the event names of the traces (simple index encoding)
and the other including the timestamps features.
Then, some classifiers are trained on the encoded
dataset, optimizing some of their hyper-parameters
through a grid-search. The best models are then
evaluated in the test set and compared.
