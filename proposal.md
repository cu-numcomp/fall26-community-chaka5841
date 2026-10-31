# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: AvaFrame

AvaFrame is an opensource framework from the Austrian Avalanche and Torrent Service and the Austrian Research Centre for Forests. It takes in terrain and a relesase point and maps the viscosity and pressure. The main solver, com1DFA, solves thickness-averaged mass and momentum balance equations. It’s a particle-mesh hybrid using smoothed particle hydrodynamics. In time, it uses operator splitting, adding one effect at a time each step.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/avaframe/AvaFrame |
| Main/documentation website | https://avaframe.org (docs: https://docs.avaframe.org) |
| Year project was started | 2020 (first commit June 29, 2020) |
| Number of contributors in the past year | 13|
| Number of contributors in the lifetime of the project | 30 |
| Number of distinct affiliations | 5-10 (AvaFrame core team, BFW Austrian Research Centre for Forests, Tyrol state government, Austrian torrent/avalanche control, ENSTA Paris, plus independents) |
| Where do development discussions take place? | GitHub issues and pull requests |
| Typical number of emails/comments per week? | About 10 |
| Typical number of commits per week? | 4ish |
| Typical commit size | 16 lines|
| How does the project accept contributions? | Pull requests on GitHub to master, using feature branches; PRs must complete a required checklist |
| Does the project have an automated test suite? | Yes (pytest suite in avaframe/tests, plus standard benchmark tests) |
| Does the project use continuous integration? | Yes. GitHub Actions runs the tests on every push and PR to master, enforces the PR checklist, and builds/uploads to PyPI |
| Does the project have an AI contribution policy? | Yes. You are supposed to record the AI contribution 1-10 for every PR |
| Are any legal/licensing steps required to contribute? | No CLA. The project is licensed under EUPL v1.2, so contributions fall under that license |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [ x] I have installed the software
- [ x] I have run at least one example
- [x ] I have run the test suite
- [ x] The test suite passes

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
