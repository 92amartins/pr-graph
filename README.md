# pr-graph
Pull Requests Graphs for Team Process Diagnosis

The idea is to analyze every PR in a project, collect number of files changed and number of commits for each PR.

Then, plot these data in a two-dimensional scatter plot.

From the graph, we will be able to see if the team have issues such as:

- Chaos (too many files, too many commits)
- Lack of Knowledge (few files, many commits)
- Too much going on (many files, few commits)
- Healthy (few files, few commits)

Of course, the definition of "few" and "many" need to be better defined.
