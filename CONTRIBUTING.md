## Contributing to Autodesk CTM

The CTM methodology is meant to evolve with community feedback - the project and its users greatly appreciate any thoughts on ways to improve the content and methodology.

### Contributing Content

The CTM methodology accepts and greatly appreciates contributions. The project follows the [fork & pull](https://help.github.com/articles/using-pull-requests/#fork--pull) model for accepting contributions.

When contributing, please also include a background explanation or scenario that justifies the contribution as part of the pull request, and follow the same comment and writing style as the rest of the project. Take a look through the existing content for examples of the testing and style practices the project follows.

Please use the `enhancement` tag to specifically denote issues that are suggestions - this helps us triage and respond appropriately.

#### Fork the project

Fork the `ctm` project with your GitHub account.

#### Create a new branch off of the `development` branch

On your fork, locally, create a new branch off of `development`.
The name of your branch should include the type of change it holds, a brief description of the changes, and the issue number if relevant.
E.g. Fixing a typo in the content as discussed in issue #101 would have a branch name like this:

```
bugs/fix-checklist-type-101
```

#### Create a pull request

When you're ready for feedback, create a pull request against the `development` branch. The title of your pull request should be a concise description of the changes within it. The description of the PR should include the reason behind your PR, a brief explanation of your approach, and highlights of any especially interesting details. If the change is visual, add a screenshot or gif to the pull request description.

A core committer will review your pull request and provide feedback or merge it into `development` as appropriate.

### Open source governance

The CTM project's chief and primary concern is with the development of a scalable threat modeling methodology that enables product teams to closely threat model their products as they evolve, improving their security posture as they go, and creating an open source library of principles which increase security-oriented efficiency and knowledge. It is NOT a substitute to secure development training, and it is NOT aimed at being the silver bullet to generate an exhaustive threat model. The CTM project's governance model thus reflects only the need to steer the direction of the content towards those aims and not any other activities which are out of scope.

Our governance model is as follows:

There is a single Tech Lead, who will have the final say on all decisions regarding technical direction.
The Tech Lead directs the Core Committers, whose members include the Tech Lead and those who have been appointed by the Tech Lead as Core Committers.
In the event the Tech Lead is unable to perform his or her duties, or abdicates, the Core Committers can select a new Tech Lead from amongst themselves.
In the event there are no Core Committers, Autodesk Inc. will appoint one.


Core Committers:

- Tech Lead: Izar Tarandach (@izar_t)
- Core Committer: Allison Schoenfield (@a_schoenfield)
