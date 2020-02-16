2019_SP13-replication_reg-report
================================

Replication of Shebani and Pulvermüller (2013) - registered report.

In accordance with the Peer Reviewers’ Openness Initiative (Morey et al., 2016),
all materials and scripts associated with this manuscript are available at
https://osf.io/ktsfw/?view_only=63e3071ba35641a0ba11785324e427e3

List of appendices (html files can be opened in any modern web browser):

- Appendix A: Systematic comparison of the original study and our replication
  following Brandt et al.’s (2014) "replication recipe".
- Appendix B: Reanalysis of the original data.
- Appendix C: Bayes factor design analysis
- Appendix D1: List of stimuli with measures on lexical and psycholinguistic
  variables
- Appendix D2: Explanation of variables in Appendix D1
- Appendix E: Analysis pipeline
- Appendix F: Counterbalancing of lists across participants
- Appendix G: Algorithm for model simplification in case of sampling issues
  during model fitting
- Appendix H: Sample size in studies investigating interference effects in
	working memory


**NB:**

Many of the simulations and analyses in Appendices B, C, and E run for a long
time on a normal computer. We have therefore saved some of the simulation
objects to file, so that they can be later retrieved to generate a report in
html format if the reader wishes to replicate the scripts. Note that all the
thus generated (knitted) html reports have been added to the repository. If you
wish to reproduce the actual analyses, you may need to uncomment some of the code
snippets. We have tried to clarify all those snippets that are commented out
because they take a long time to compute.

Some objects are too large to be uploaded to Github:

- In appendix B, the models fitted to the original data do not take a long
  time to fit, but they are quite large. You will need to run the `fit_brm()`
  function before you can run any of the other scripts, as this generates the
  model that is loaded from other appendices.
- The simulations for the BFDA (Appendix C) result in a very large file if
  you aim for 1000+ simulations. We have included a lite version of about 200
  simulations per sample size and simulation type in the repo. The file that
  stores the full set of simulations (60000 converged ones plus all the
  non-converged ones) has around 1.5 GBs. It also ran for several days on a
  computer cluster.
- Also for Appendix E, the objects (fitted models) created by the
  function `analyse_pipe()` are too large for Gitub. If you wish to generate
  the knitr report yourself, you will have to re-run those analyses on your
  computer by uncommenting the relevant snippets.

For all cases above, the results might not be identical to what we report
because we have not used random seeds for the models fitted with `brms`.
However, the differences should be negligible and should not affect any
of the conclusions.

If you have questions or wish to give feedback, please send an email to
guillermo.monteromelis@mpi.nl
