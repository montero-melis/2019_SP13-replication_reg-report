2019_SP13-replication_reg-report
================================

Replication of Shebani and Pulvermüller (2013) - registered report.

In accordance with the Peer Reviewers’ Openness Initiative (Morey et al., 2016),
all materials and scripts associated with this manuscript are available at
https://osf.io/ktsfw/?view_only=63e3071ba35641a0ba11785324e427e3

List of appendices:

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


*NB:*

Many of the simulations and analyses in Appendices A, B, and E run for a long
time on a normal computer. We have therefore saved some of the simulation
objects to file, so that they can be later retrieved to generate a report in
html format. We have also added all of the thus generated html reports to the
repository. If you wish to reproduce the actual analyses, you may need to
uncomment some of the code snippets. We have tried to clarify all those snippets
that are commented out because they take a long time to compute.

In particular for Appendix E, the objects (fitted models) created by the
function `analyse_pipe()` are too large to upload to github. If you wish to
generate the knitr report yourself, you will have to re-run those analyses
on your computer by uncommenting the relevant snippets.

If you have questions or wish to give feedback, please send an email to
guillermo.monteromelis@mpi.nl
