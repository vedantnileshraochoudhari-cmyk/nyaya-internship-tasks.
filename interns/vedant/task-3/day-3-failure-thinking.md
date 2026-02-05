# Day 3 — Failure Thinking

This task can fail if the input sentences are empty or not in correct format.

If the number of embeddings does not match the number of sentences, clustering will not work.

If embeddings are not numeric or have different sizes, KMeans will give an error.

If output files are not saved properly, results can be lost even if the code runs.

Because of these reasons, it is important to check inputs and outputs before trusting the results.
